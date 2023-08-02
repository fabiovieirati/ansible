In this README i'll show my evolution using the fantastic toll Ansible.

Frist lets create a file with name host, then put in side there your endpoint ex:
[endpoint]
192.168.0.1
192.168.0.2

i use the command bellow to explain in shell the frase 'Hello World'
`ansible vm -u root -i hosts -m shell -a 'echo Hello, World'`
