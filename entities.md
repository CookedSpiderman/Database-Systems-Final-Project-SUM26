**Entities:**

1. parts made/bought
2. suppliers
3. people
4. departments
5. marketing sites
6. Employee



**Attributes:**

Department: DepID, DepName

Person: PersonalID, Lname, Fname, Age, Gender, Address, PhoneNum

Employee:PersonalID(from Person) ,Rank, Title, SupervisorID, dept ID(from , deptStartTime, deptEndTime



**Relations:**

Person -> can be employee, sales rep, customer, potential employee



Employee -> has ONE supervisor, may work for ONE department,



Supervisor -> manages N employees



**Resolutions:**

1. Made an interview entity rather than just having the DCI Relation



**Assumptions:** 

1. There is not total participation for SUPERVISION because CEO will not have supervisor

