# 20483C_MOD08_LAK_EX2
Exercise 2: Integrating the Data Service into the Application

JOSE VICENTE TEJERO CALDERERA - 01/11/2020

RESUMEN.
Task 1.- Add an OData Connected Service for the WCF Data Service to the GradesPrototype application

<service xmlns="http://www.w3.org/2007/app" xmlns:atom="http://www.w3.org/2005/Atom" xml:base="http://localhost:1655/Services/GradesWebDataService.svc/">
<workspace>
<atom:title>Default</atom:title>
<collection href="Grades">
<atom:title>Grades</atom:title>
</collection>
<collection href="Students">
<atom:title>Students</atom:title>
</collection>
<collection href="Subjects">
<atom:title>Subjects</atom:title>
</collection>
<collection href="Teachers">
<atom:title>Teachers</atom:title>
</collection>
<collection href="Users">
<atom:title>Users</atom:title>
</collection>
</workspace>
</service>

Task 2: Modify the code that accesses the EDM to use the WCF Data Service
Task 3: Modify the code that saves changes back to the database to use the WCF Data Service
Task 4: Build and test the application to verify that the application still functions correctly



PROBLEMAS
Ninguno
