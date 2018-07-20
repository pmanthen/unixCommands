# unixCommands
Helpful unix commands

Consider parameterizing secret values in code and replace during build (In Jenkins)
`sed -i -e 's/$password/'"${password}"'/g' prod.properties` //Thiw will replace `$password` in file with `$passowrd` Unix variable. Consider populating this variable through some KMS system

`sed -i 's/^start_rpc.*$/start_rpc: true/'` will replace the line that has `start_rpc` with `start_rpc: true` 

docker inspect ip address:
`docker inspect <container id> | grep "IPAddress"`

Docker prune all
`docker system prune --all --force --volumes`

Install telnet ` sudo apt-get update && apt-get install telnet`

Run a pod with just ubuntu `kubectl run my-shell --rm -i --tty --image ubuntu -- bash`

Ssh to pod kubectl `exec -it shell-demo -- /bin/bash`
