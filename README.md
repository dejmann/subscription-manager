# subsciption-manager

Red Hat subscription-manager package that has been built to work with Oracle Linux 8.

Oracle removed subsciption-manager from their repositories, which meant Oracle Linux 8 servers could not be registered to Foreman Katello or Satellite.

Use this subscription-manager package for use with Foreman Katello and Satellite

# Installation

Either download the RPMs from this Git repoistory.

or;

1) wget https://copr.fedorainfracloud.org/coprs/dmann/subscription-manager/repo/epel-8/dmann-subscription-manager-epel-8.repo
2) mv dmann-subscription-manager-epel-8.repo /etc/yum.repos.d/
3) Run 'yum install -y subscription-manager'

# Version History

27th July 2021 - 1.29.18-1.el8

New versions will be released when subsciption-manager is updated.
