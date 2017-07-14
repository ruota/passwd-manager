# passwd-manager
A little script app to manage encrypted passwords, it depends from openssl

Start: PASSDB=pass.db passwd-manager --init

passwd-manager PASSDB=<password db> option
options: 
    --init
    --insert <user> <password>
    --remove <user>
    --show <user | all>
    --password
