
This is a very basic single-file playbook, it aims at being a starting point
for anyone willing to give Ansible a try.
As an example, this sets up a Debian system with the very basic tools you might want to use as a developer.

Prepare the targeted system(s):

    $ ansible-playbook -K -i 192.168.1.71, essentials.yml --extra-vars "myuser=foo myghuser=foo_github"

pass the `new=yes` variable if this is a new environment to setup
