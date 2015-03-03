devstack-fwaas
==============
Devstack and FWAAS localrc

Prerequisites:
--------------
- DevStack setup requires to have 1 VM/ BM machine with internet connectivity.
- Setup a fresh supported Linux installation. (Ubuntu/Fedora/CentOs)
- Install Git

Steps
-----
1. Clone devstack
```
$git clone https://github.com/openstack-dev/devstack.git
```

2. Clone devstack-fwaas
```
$git clone https://github.com/svashu/devstack-fwaas.git
```

3. Copy localrc from devstack-fwaas to devstack
```
$ cp devstack-fwaas/localrc devstack

```

4. Modify the devstack/localrc for IP and password modifications

5. Deploy your Devstack

```
$cd devstack && ./stack.sh
```
