# Exerc-cio-Aula-2

nosql@virtualbox:~/Aulas/mongodb$ ./bin/mongo
MongoDB shell version: 3.2.10
connecting to: test
Server has startup warnings:
2016-11-10T19:43:08.857-0200 I CONTROL [initandlisten]
2016-11-10T19:43:08.857-0200 I CONTROL [initandlisten] ** WARNING: /sys/kernel/mm/transparent_hugepage/enabled is 'always'.
2016-11-10T19:43:08.857-0200 I CONTROL [initandlisten] ** We suggest setting it to 'never'
2016-11-10T19:43:08.857-0200 I CONTROL [initandlisten]
2016-11-10T19:43:08.857-0200 I CONTROL [initandlisten] ** WARNING: /sys/kernel/mm/transparent_hugepage/defrag is 'always'.
2016-11-10T19:43:08.857-0200 I CONTROL [initandlisten] ** We suggest setting it to 'never'
2016-11-10T19:43:08.857-0200 I CONTROL [initandlisten]

^C
bye
nosql@virtualbox:~/Aulas/mongodb$ cd /Aulas/mongodb
nosql@virtualbox:/Aulas/mongodb$ ./bin/mongo
MongoDB shell version: 3.2.10
connecting to: test
Server has startup warnings:
2016-11-10T19:43:08.857-0200 I CONTROL [initandlisten]
2016-11-10T19:43:08.857-0200 I CONTROL [initandlisten] ** WARNING: /sys/kernel/mm/transparent_hugepage/enabled is 'always'.
2016-11-10T19:43:08.857-0200 I CONTROL [initandlisten] ** We suggest setting it to 'never'
DBCollection.prototype._validateForStorage@src/mongo/shell/collection.js:252:1
DBCollection.prototype._validateForStorage@src/mongo/shell/collection.js:256:13
Bulk/this.insert@src/mongo/shell/bulk_api.js:652:17
DBCollection.prototype.insert@src/mongo/shell/collection.js:344:13
@(shell):1:1
db.Alunos.insert({ "name":"Leonardo", "birthday":ISODate("1987-22-04T00:00:00Z"), "group": "Grupo 1" })
WriteResult({ "nInserted" : 1 })
db.Alunos.insert({ "name":"Briner", "birthday":ISODate("1988-07-11T00:00:00Z"), "group": "Grupo 1" })
WriteResult({ "nInserted" : 1 })
db.Alunos.insert({ "name":"Fabrício", "birthday":ISODate("1987-09-12T00:00:00Z"), "group": "Grupo 1" })
WriteResult({ "nInserted" : 1 })
db.Alunos.insert({ "name":"Eduardo", "birthday":ISODate("1986-27-11T00:00:00Z"), "group": "Grupo 1" })
WriteResult({ "nInserted" : 1 })
db.Alunos.update({
... "name":"Leonardo"},
... {$set:{
... "Disciplina cursada":"IEL",
... "Disciplina em curso":"NOsql"
... }
... }
... )
WriteResult({ "nMatched" : 1, "nUpserted" : 0, "nModified" : 1 })
db.Alunos.update({ "name":"Briner"}, {$set:{ "Disciplina cursada":"IEL", "Disciplina em curso":"NOsql" } } )
WriteResult({ "nMatched" : 1, "nUpserted" : 0, "nModified" : 1 })
db.Alunos.update({ "name":"Fabrício"}, {$set:{ "Disciplina cursada":"IEL", "Disciplina em curso":"NOsql" } } )
WriteResult({ "nMatched" : 1, "nUpserted" : 0, "nModified" : 1 })
db.Alunos.update({ "name":"Eduardo"}, {$set:{ "Disciplina cursada":"IEL", "Disciplina em curso":"NOsql" } } )
WriteResult({ "nMatched" : 1, "nUpserted" : 0, "nModified" : 1 })
db.Alunos.find({"name":"Eduardo"})
{ "_id" : ObjectId("5824f040c06536e243b3e661"), "name" : "Eduardo", "birthday" : ISODate("1988-03-11T00:00:00Z"), "group" : "Grupo 1", "Disciplina cursada" : "IEL", "Disciplina em curso" : "NOsql" }
db.Alunos.update({ "name":"Eduardo"}, {$set:{ "Disciplina cursada":"IEL""IBD", "Disciplina em curso":"NOsql" } } )
2016-11-10T20:25:45.577-0200 E QUERY [thread1] SyntaxError: missing } after property list @(shell):1:72
db.Alunos.update({ "name":"Eduardo"}, {$set:{ "Disciplina cursada":"IEL","IBD", "Disciplina em curso":"NOsql" } } )
2016-11-10T20:25:56.162-0200 E QUERY [thread1] SyntaxError: missing : after property id @(shell):1:78
db.Alunos.update({ "name":"Eduardo"}, {$set:{ "Disciplina cursada":"IEL", "Disciplina em curso":"NOsql" } } )
WriteResult({ "nMatched" : 1, "nUpserted" : 0, "nModified" : 0 })
db.Alunos.find({"name":"Eduardo"})
{ "_id" : ObjectId("5824f040c06536e243b3e661"), "name" : "Eduardo", "birthday" : ISODate("1988-03-11T00:00:00Z"), "group" : "Grupo 1", "Disciplina cursada" : "IEL", "Disciplina em curso" : "NOsql" }
db.Alunos.update({ "name":"Eduardo"}, {$set:{ "Disciplina cursada":"IEL", "Disciplina em curso":"NOsql", "Nota":5 } } )
WriteResult({ "nMatched" : 1, "nUpserted" : 0, "nModified" : 1 })
db.Alunos.update({ "name":"Briner"}, {$set:{ "Disciplina cursada":"IEL", "Disciplina em curso":"NOsql", "Nota":7 } } )
WriteResult({ "nMatched" : 1, "nUpserted" : 0, "nModified" : 1 })
db.Alunos.update({ "name":"Leonardo"}, {$set:{ "Disciplina cursada":"IEL", "Disciplina em curso":"NOsql", "Nota":4 } } )
WriteResult({ "nMatched" : 1, "nUpserted" : 0, "nModified" : 1 })
db.Alunos.update({ "name":"Fabrício"}, {$set:{ "Disciplina cursada":"IEL", "Disciplina em curso":"NOsql", "Nota":8 } } )
WriteResult({ "nMatched" : 1, "nUpserted" : 0, "nModified" : 1 })
db.Alunos.find({},{"birthday":1, _id:0}).sort({"birthday":1})
{ "birthday" : ISODate("1987-09-12T00:00:00Z") }
{ "birthday" : ISODate("1988-03-11T00:00:00Z") }
{ "birthday" : ISODate("1988-07-11T00:00:00Z") }
{ "birthday" : ISODate("1988-10-04T00:00:00Z") }
db.Alunos.remove({"name":"Leonardo"})
WriteResult({ "nRemoved" : 1 })
