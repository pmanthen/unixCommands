# unixCommands
Helpful unix commands

Consider parameterizing secret values in code and replace during build (In Jenkins)
sed -i -e 's/$password/'"${password}"'/g' prod.properties //Thiw will replace $password in file with $passowrd Unix variable. Consider populating this variable through some KMS system
