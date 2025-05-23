1.wsl --install        2.sudo apt update     3.sudo apt install ansible -y            4.ansible --version.                             5.mkdir ~/ansible-lab.   6.cd ~/ansible-lab.    7.nano hosts.      In the editor, type the following:
[local]
localhost ansible_connection=local.                 in cmd:  ansible -i hosts local -m ping