# unixCommands
Helpful unix commands

Consider parameterizing secret values in code and replace during build (In Jenkins)
sed -i -e 's/$password/'"${password}"'/g' prod.properties //Thiw will replace $password in file with $passowrd Unix variable. Consider populating this variable through some KMS system

`sed -i 's/^start_rpc.*$/start_rpc: true/'` will replace the line that has start_rpc with `start_rpc: true` 
