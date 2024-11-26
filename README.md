# naemon-thruk-rpms
These are my rpm spec files for [Naemon](https://www.naemon.io/), [Thruk](https://thruk.org/) and other playing parts to do monitoring.

# Description
Here are Monitoring rpm spec files for [Naemon](https://www.naemon.io/) / [Thruk](https://thruk.org/) and all that i use around them.  
Build and tested for/with [Red Hat Enterprise Linux Server](https://www.redhat.com/en/technologies/linux-platforms/enterprise-linux/server) 9
or clones like [AlmaLinux](https://almalinux.org/), [Rocky Linux](https://rockylinux.org/).  
It is based on the spec files from [home:naemon - openSUSE Build Service](https://build.opensuse.org/project/show/home:naemon).  
My goal is to build all with only spec files and get sources from git repos.

# Build rpms
You can build rpms from just the spec file with `spectool -gf -R <spec>` and `rpmbuild -bb <spec>` except gearmand
(3 files from source dir needed too).