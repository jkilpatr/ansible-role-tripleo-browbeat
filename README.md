# ansible-role-tripleo-browbeat

This is an Ansible role for [Openstack TripleO Quickstart](https://github.com/openstack/tripleo-quickstart) designed to allow
users of oooq in continuous integration to easily consume Browbeat and perform benchmarking on their clouds during testing.

Right now this is in Alpha and does not provide many options, but the goals moving forward are to provide a more compete set
of benchmarking options easily configurable be exporting variables from your oooq invocation and possibly even benchmarks
driven by Ansible fact gathering to auto tune themselves for target hardware.

To use this role add this repository to your tripleo-role-requirements.txt file and either use one of the provided playbooks
or refer to them and add their Browbeat call to your own playbook.
