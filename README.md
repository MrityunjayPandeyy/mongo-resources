# mongo-resources
Resource for Mongo DB


#Current open Connetions on mongodb
db.currentOp(true).inprog.forEach(function(d){if(d.client)print(d.client, d.connectionId)})
