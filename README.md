![Ansible Galaxy](https://github.com/BasisTI/ansible_kubetools/workflows/Ansible%20Galaxy/badge.svg)

Ansible Role: Kubetools
=========

An Ansible Role that installs some tools such as kubectl, helm and helmfile on RHEL/CentOS/Fedora and Debian/Ubuntu.

Role Variables
--------------

Available variables are listed below, along with default values (see defaults/main.yml):

    kubectl_bin_path: /usr/local/bin/kubectl
    helm_bin_path: /usr/local/bin/helm
    helmfile_bin_path: /usr/local/bin/helmfile

You can specify install path for the binaries.

    kubectl_version: ''
    helm_version: v3.3.0
    helmfile_version: v0.125.7

You can specify the binaries version. If not specified kubectl_version the kubectl tool will be installed with the release version.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: basisconfig.kubetools }

License
-------

BSD
