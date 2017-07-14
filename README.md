# passwd-manager
A little script app to manage encrypted passwords, it depends from openssl

passwd-manager PASSDB=<password db> option
options: 
    --init
    --insert <user> <password>
    --remove <user>
    --show <user | all>
    --password
