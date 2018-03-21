Role Name
=========

KONG 

Requirements
------------

cpu support sse4.2

```
cat /proc/cpuinfo | grep sse4_2
```
[Reference](https://medium.com/@nprch_12/docker-exited-132-e38f9dd2cd0d)

Role Variables
--------------

unnecessary for beginner

Dependencies
------------

unnecessary for beginner

Example Playbook
----------------

It's so easy to start service Kong on docker by Ansible

```
    - hosts: serverA
      roles:
         - kong

```

Command run to install

```
 ansible-playbook -i hosts example.yml --tags "install"
```
 
Can check service with tag

``` 
 --tags "run"
```

And clear container kong & database with tag

```
 --tags "removeall"
```

Author Information
------------------

Free Licenses CPA.GO.TH

