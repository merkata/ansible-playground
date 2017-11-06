# ansible-playground
Some ansible testing with VMs

# instructions
When playing with this playground, please consider the rule of the config file lookup:

```
* ANSIBLE_CONFIG (an environment variable)
* ansible.cfg (in the current directory)
* .ansible.cfg (in the home directory)
* /etc/ansible/ansible.cfg
```

So make sure to clone the repo and either export 'ANSIBLE_CONFIG' or be in the cloned directory that contains ansible.cfg. Your config might be in a different branch than master.
