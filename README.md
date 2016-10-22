# OOAD-WEEK09
Class Diagram

ข้อ1
```
@startuml
abstract class CheckList
abstract Collection
interface List
interface item

List <|-- CheckList
item <|-- Collection

item <|- List 
Collection <|- CheckList
CheckList <|-- Customer

class Customer { 
}

@enduml
```
![](http://www.plantuml.com/plantuml/img/JOwx3OH034HpL-46w800YPGcVCQ8rUr7MW_P5N_yn9BPR-od6HnIiQL8yd5KKR16SUTnDVrEmT62iSHeYb0oXGohYwZnUTBM04j41-J-rtKlpP7SxEMvuQLfmScUNwOsNeRDKP9Lei7olBV_0m00)

ข้อ2
```
@startuml
class man {
use
}

class clock {
set
start
stop
exit
}

class time {
months
hours
minutes
}

man --> clock
clock --> time

@enduml
```
![](http://www.plantuml.com/plantuml/img/LOv12i0W30Jl-ufye5_eNqG2Ieqf9a91-lTYBxMNFUmEmyOIpCYpC0s8La-6fBqP9DVkRBY1-4AnQ3m6Z1tceStK4tnb_nW9TQ0R_nhQjfqMn-fRjda2m0C0)

ข้อ3
```
@startuml
class Jib {
}

class Joy {
}

class Kay {
}

Jib - Joy
Joy - Kay

@enduml
```
![](http://www.plantuml.com/plantuml/img/AybFJot9I2rIgEPApaaiBbRmoapYWZ7pAs5CxyHAhbekBg2aWYvO78Y1BA0m0000)

ข้อ4
```
@startuml
class Student {
Name 
id
} 

class Course{
english
math
}

Student "0..*" -- "1..*" Course
(Student, Course) . Enrollment

class Enrollment {
delete()
clear()
cancel()
}

@enduml
```
![](http://www.plantuml.com/plantuml/img/HOun2iCm34LtdK9uIafZsXi4IjSkEO68HHEG7R3bgVJkKLgNJlhyfw-liIXbhL5W5Ye59ws1a-8B7XGPrW3lHcvRpOKDS7hAMXQ8f8jH-4NSnVkJms50T_seRmAwjd1kHeyUxobl8j5SQEV_ZbK45bRkUcDC-PYKPXOJrZTo2iV3Em00)

ข้อ5
```
@startuml
ClassRoom o- Student 
ClassRoom *-- Chair
ClassRoom *-- Table
ClassRoom o- Teacher
ClassRoom *-- Prejector
ClassRoom *-- Computer
@enduml
```
![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuNBEIImk3ihFprN8rrK8BYbDISqhKK0IrTBLLN3EICmiGXCBIKpAIKNL7PAQc9oHYgume2WrApMv91zTt3a_jw2q1AZS8JKl1UWI0000)

