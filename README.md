# Customer-Management-App-
Created Customer Management App in Python Using Flask and  NoSql Database -> MongoDb with basic CRUD operations 

1. Create a Class in Python using OOPS
    Customer
        id, name, phone, email, createdOn, remarks, points, type
2. Create a Table in MySQL using the attributes of your Object
3. Create a Class DataBaseHelper where you will create write and read operations for the table
4. Create a Flask Web App
    4.1 Create a Web Page which has fields to insert data
        Here, fileds will be as per the number of attributes
        As per our project, id and createdOn is automatic
        Hence, 6 UI Web Elements must be thr
    4.2 Create a Web Page which has a table to display records


#Homepage
![cms1](https://user-images.githubusercontent.com/81138092/189519999-013e1137-3c1c-4f1f-87f1-007d7a588bd4.png)

#Add Customer
![cms3](https://user-images.githubusercontent.com/81138092/189520258-8369565d-9973-4303-b536-fa7dc048d57c.png)

![cms2](https://user-images.githubusercontent.com/81138092/189520257-12c24518-0a78-4d10-9248-580341e28e14.png)



#View Customer
![cms4](https://user-images.githubusercontent.com/81138092/189520262-a58561fc-95ac-45be-8f3b-a41412332e71.png)
#Delete Customer
![cms5](https://user-images.githubusercontent.com/81138092/189520400-93701a6f-ecc6-4c15-8709-7c8ff059f4d3.png)
#Update Customer

![cms6](https://user-images.githubusercontent.com/81138092/189520401-0c66466b-7c9f-4247-a9f6-cd14b43b6b88.png)


Data is saved In MONGODB  as -
{"_id":{"$oid":"63147f0dc355ff02cd7e62ab"},"id":null,"name":"John","phone":"9999911111","email":"john@example.com","created_on":null,"remarks":"Interested in devops","points":{"$numberInt":"100"},"type":{"$numberInt":"1"}}
{"_id":{"$oid":"631ac082da1e138856724834"},"id":null,"name":"Mike","phone":"8974510135","email":"mike@gmail.com","created_on":null,"remarks":"In for Java","points":{"$numberInt":"100"},"type":{"$numberInt":"1"}}
{"_id":{"$oid":"631da68a0bbae834741a2f7e"},"id":null,"name":"ria","phone":"8745103654","email":"ria@mail.com","created_on":null,"remarks":"In for Git and Github","points":{"$numberInt":"100"},"type":{"$numberInt":"1"}}
