# ElectricCarMotorJava
Rest API application:
This is done in Java using Repositoryes,Services and Models with Spring Boot and Angular for frontend.
 - Client (id, company name,car name, date of registration, number of total motors, total sum of motors)
 - Car (id, name, motor power needed)
 - Motor (id, technology, price, power, engine consumption, compatible with(Tesla,BMW,VW,Renault), number of engines returned )
 - Transaction (id, company name, car id, motor id, price, number of pieces, date of transaction, total sum)

This app uses API and stores the data in a JSON server, then it shows the entityes added in a table in a Angular frontend webpage. The frontend was created using Angular 16.0.0 and Material.
1. Entityes are added with the command line in Java application (Future update: the ability to add entityes from Angular webpage )
2. Transaction service, check if the car gets an engine with the needed power.
3. Add return of a motor ( Future update: If there are >100 motor sent back then that type of engine will not be sold untill it`s fixed)
