# My Application

The project is generated by [LoopBack](http://loopback.io).

#Application generation
lb

#Database Connectivity (MySQL connector)
lb datasource

#Sample Model creation with some props
$ lb model
? Enter the model name: Employee
? Select the datasource to attach Employee to: mysql (mysql)
? Select model's base class PersistedModel
? Expose Employee via the REST API? Yes
? Custom plural form (used to build REST URL): employees
? Common model or server only? common
Let's add some Employee properties now.

Enter an empty property name when done.
? Property name: name
? Property type: string
? Required? Yes
? Default value[leave blank for none]:

Let's add another Employee property.
Enter an empty property name when done.
? Property name: salary
? Property type: number
? Required? Yes
? Default value[leave blank for none]: 0

Let's add another Employee property.
Enter an empty property name when done.
? Property name: organisation
? Property type: string
? Required? Yes
? Default value[leave blank for none]:

Let's add another Employee property.
Enter an empty property name when done.
? Property name: address
? Property type: string
? Required? No
? Default value[leave blank for none]:

Let's add another Employee property.
Enter an empty property name when done.
? Property name: createdDate
? Property type: date
? Required? Yes
? Default value[leave blank for none]:

Let's add another Employee property.
Enter an empty property name when done.
? Property name:

#Discovering Models from Database

npm install loopback-connector-mysql --save