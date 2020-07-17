# awsrdsvideo
commands to run on ec2 instance to connect to db and then create table


sudo yum install mysql
mysql -h <your db instance endpoint> -P 3306 -u master -p
show databases;
use rds;
creat table awsrdsvideo (name VARCHAR(30), batch INT(2), phone VARCHAR(10), EMAIL VARCHAAR(30));
insert into awsrdsvideo values ('Myra', 3, '7x5x9x3x8x', 'xxxx@gmail.com');
select * from awsrdsvideo
