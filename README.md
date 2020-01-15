# azureTerrafiorm

In your cloud shell

`mkdir .ssh`
`cd .ssh`
`ssh-keygen `

enter 2 times to create the file

you should see two files

total 8

-rw------- 1 meera meera 1675 Jan 15 04:47 id_rsa

-rw-r--r-- 1 meera meera  416 Jan 15 04:47 id_rsa.pub


# create authorized_keys using the below command

~/.ssh$ `cat ~/.ssh/id_rsa.pub >> ~/.ssh/authorized_keys`

create a directory tftest

mkdir tftest

cd tftest

upload the main.tf file

terraform init

terraform plan

terraform apply

when asked for "yes", press "yes"

you will see an vm get created.
