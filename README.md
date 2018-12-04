**study ansbile to configule**

Mac install ansible ```brew install ansible```

Missing ```/etc/ansible``` files for ```brew``` installation

Copy the contents of the ```examples``` file to ```/etc/ansible```

Edit ```hosts``` file  ```vim /etc/ansible/hosts```

- [webservers]

```101.112.65.20```
```47.96.70.141```


Through command line look up ```ansible all -m ping -u root```

We can also customize our requirements through ansible 

Playbook official Learning document

https://ansible-tran.readthedocs.io/en/latest/docs/playbooks_intro.html#about-playbooks

**Example**

```mkdir /etc/ansible/playbooks/test.yml```


