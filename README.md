Create table Employee(id int primary key,name nvarchar(60),salary int);
insert into employee values(1,"raju",4000);
insert into employee values(2,"ramu",5000);
insert into employee values(3,"sita",3500);
select*from employee;
update employee set salary=6000 where id=2;
select distinct id from employee where id=2;
select*from employee order by salary desc;
select*from employee where id=3;

