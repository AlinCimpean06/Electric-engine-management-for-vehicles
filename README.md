# ElectricCarMotorJava
App that is done in Java using Repositoryes,Services and Models with Spring Boot and Angular for frontend.
 - Client (id, company name, date of registration, number of total motors, total sum of motors)
 - Car (id, name, motor power needed)
 - Motor (id, technology, price, power, engine consumption, compatible with(Tesla,BMW,VW,Renault), number of engines returned )
 - Transaction (id, company name, car id, motor id, price, number of pieces, date of transaction, total sum)

1. Transaction service, check if the car gets an engine with the needed power.
2. Discount by number of engines bought, (>1000 then 5% discount, >2000 then 10% discount)
3. Sort the clients by the highes total sum of motors
4. Add return of a motor and if there are >100 motor sent back then that type of engine will not be sold untill it`s fixed.
