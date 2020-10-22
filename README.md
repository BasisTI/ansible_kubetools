# Ansible Role: Kubetools


An ansible role that installs kubernetes tools on rhel/centos/fedora and debian/ubuntu. 

![Ansible Galaxy](https://github.com/BasisTI/ansible_kubetools/workflows/Ansible%20Galaxy/badge.svg)

## Tags:
## Variables:

* `kubectl_bin_path`: `/usr/local/bin/kubectl` - You can specify install path for the kubectl.



* `helm_bin_path`: `/usr/local/bin/helm` - You can specify install path for the helm.



* `kubectl_version`: `` - By default kubectl_version is undefined, it will be get the stable version on the https://storage.googleapis.com/kubernetes-release/release/stable.txt.



* `helm_version`: `v3.3.0` - You can specify the helm version.



* `helmfile_bin_path`: `/usr/local/bin/helmfile` - You can specify install path for the helmfile.



* `helmfile_version`: `v0.125.7` - You can specify the helmfile version.


## License
Mit



Documentation generated using: [Ansible-autodoc](https://github.com/AndresBott/ansible-autodoc)

