- 👋 Hi, I’m @lzjaa120
- 👀 I’m interested in SQL
- 🌱 I’m currently learning GIT
- 💞️ I’m looking to collaborate on compete
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

CREATE DATABASE studentsdb;
USE studentsstudentdbdb;
CREATE TABLE student_info(学号 CHAR (4) NOT NULL,
姓名 CHAR (8) NOT NULL,
性别 CHAR (2),
出生日期 DATE,
家庭住址 VARCHAR (50));
INSERT INTO student_info(学号,姓名,性别,出生日期,家庭住址)
VALUES('0001','张青平','男','2001/10/1','衡阳市东风路77号'),
('0002',	'刘东阳','男','1998/12/09','东阳市八一北路33号'),
('0003','马晓夏','女','1995/05/12','长岭市五一路763号'),
('0004','钱忠理','男','1994/09/23','滨海市洞庭大道279号'),
('0005','孙海洋','男','1995/04/03','长岛市解放路27号'),
('0006','郭小斌','男','1997/11/10','南山市红旗路113号'),
('0007','肖月玲','女','1996/12/07','东方市南京路11号'),
('0008',	'张玲珑','女','1997/12/24','滨江市新建路97号');	
