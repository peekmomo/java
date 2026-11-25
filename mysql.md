### relational  non-relational

### database management system
    create database name;
    use name;
    drop database name;
    alter database name read only=1;

### create table
    CREATE TABLE employee(
    employee_id INT,
    first_name VARCHAR(50),
    last_name VARCHAR(50),
    hourly_pay DECIMAL(5,2),
    hire_data DATE
 );
    rename table employee to works;
    alter table employees add phone_number varchar(15)

alter:
 操作	SQL 关键字	作用
添加字段	ADD	增加列
修改字段类型	MODIFY	修改列的数据类型
修改字段名称	CHANGE	修改列名及定义
删除字段	DROP COLUMN	删除列
修改表名	RENAME TO	修改表名称

### insert
    insert into employees() values(),(),()

### SELECT
    select * from employees where

### update
   update employees set where

### START TRANSACTION;
   sql默认autocommit=1
   除非开始事务，使用commit或者rollback

### ADD CONSTRAINT UNIQUE

### check
  约束检查 
  限制插入数据库的数据必须满足指定条件，不满足条件就不允许插入或修改
  alter table employees drop check checkname

### default

### primary key
    unique and not null

### foregin key
    foregin key () references employee(employee_id)
     alter table customer drop foregin key 

### joins
    inner left right

### function
   count max min

### order by
desc asc

### limit
### union

### self join
### group by