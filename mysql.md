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
    insert into employees values()
    