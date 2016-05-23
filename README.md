# vagrant-mongo-dev
It's a simple vagrant provisioned just with mongodb for development purpose.

If you need to reach mongo from the host you have to modify the '/etc/mongo.conf' file adding
    `# bind = 127.0.0.0`
then
    `service mongod restart`
