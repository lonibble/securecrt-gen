# Create Secure CRT Connection files

## Edit the var.csv
Filename is the hostname of the system.

Port need to be in HEX!

    For example port 22 would be 00000016
    For example port 3001 would be 00000bb9

## Run the play
' ansible-playbook scrt-create.yml'
