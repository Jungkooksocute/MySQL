**����Ա��ʽ���� �ն�**

## mysql day01���ñʼ�

1��ʲô�����ݿ⣿ʲô�����ݿ����ϵͳ��ʲô��SQL������֮��Ĺ�ϵ��ʲô��

	���ݿ⣺
		Ӣ�ĵ���DataBase�����DB������һ����ʽ�洢���ݵ�һЩ�ļ�����ϡ�
		����˼�壺�洢���ݵĲֿ⣬ʵ���Ͼ���һ���ļ�����Щ�ļ��д洢��
		�����ض���ʽ�����ݡ�
	
	���ݿ����ϵͳ��
		DataBaseManagement�����DBMS��
		���ݿ����ϵͳ��ר�������������ݿ������ݵģ����ݿ����ϵͳ����
		�����ݿ⵱�е����ݽ�����ɾ�Ĳ顣
	
		���������ݿ����ϵͳ��
			MySQL��Oracle��MS SqlServer��DB2��sybase��....
	
	SQL���ṹ����ѯ����
		����Ա��ҪѧϰSQL��䣬����Աͨ����дSQL��䣬Ȼ��DBMS����ִ��SQL
		��䣬������������ݿ������ݵ���ɾ�Ĳ������
	
		SQL��һ�ױ�׼������Ա��Ҫѧϰ�ľ���SQL��䣬���SQL��mysql�п���ʹ�ã�ͬʱ��Oracle��Ҳ����ʹ�ã���DB2��Ҳ����ʹ�á�
	
	����֮��Ĺ�ϵ��
		DBMS--ִ��--> SQL --����--> DB
	
	�Ȱ�װ���ݿ����ϵͳMySQL��Ȼ��ѧϰSQL�����ôд����дSQL���֮��DBMS
	��SQL������ִ�У�������������ݿ�����ݹ���


2����װMySQL���ݿ����ϵͳ��
	��һ�����Ȱ�װ��ѡ�񡰾���桱
	�ڶ�������Ҫ����MySQL���ݿ�ʵ�����á�

	ע�⣺һ·��һ�������ˣ���������
	
	��Ҫע������
		�˿ںţ�
			�˿ں�port���κ�һ�����/Ӧ�ö����еģ��˿ں���Ӧ�õ�Ψһ����
			�˿ں�ͨ����IP��ַ��һ�飬IP��ַ������λ������ģ��˿ں�port
			��������λ�������ĳ�������/ĳ��Ӧ�õģ�
			��ͬһ̨������ϣ��˿ںŲ����ظ�������Ψһ�ԡ�
	
			mysql���ݿ�������ʱ���������ռ�е�Ĭ�϶˿ں���3306
			���Ǵ�Ҷ�֪�����¶�����ס��
		
		�ַ����뷽ʽ��
			����mysql���ݿ���ַ����뷽ʽΪ UTF8
			һ��Ҫע�⣺��ѡ�е�3����ѡ��ť��Ȼ����ѡ��utf8�ַ�����
		
		�������ƣ�
			Ĭ���ǣ�MySQL
			���øġ�
		
		ѡ�����û�������path��
			���û��ѡ����ô�죿������ֶ�����
			path=����·��;C:\Program Files (x86)\MySQL\MySQL Server 5.5\bin
		
		mysql��������Ա�û������ܸģ�һ���ǣ�root
		����Ҫ����mysql���ݿⳬ������Ա�����롣
		�������ֻ�����
	
		���������ͬʱ�����Լ���root�˻�Զ�̷��ʡ�
		�����ʾroot�˺ſ�������ص�¼��
		�������ʾroot�˺�ֻ���ڱ�����ʹ�á�
		������ѡ�񼤻��ˣ�

3��MySQL���ݿ������ж�أ�
	��һ����˫����װ������ж��ɾ����
	�ڶ�����ɾ��Ŀ¼��
		��C:\ProgramData�����MySQLĿ¼�ɵ���
		��C:\Program Files (x86)�����MySQLĿ¼�ɵ���

	������ж�ؽ����ˣ�

4����һ�¼�����ϵķ�����һ��MySQL�ķ��������
	�����-->�Ҽ�-->����-->�����Ӧ�ó���-->����-->��mysql����
	MySQL�ķ���Ĭ���ǡ���������״̬��ֻ��������mysql�����á�
	Ĭ��������ǡ��Զ����������Զ�������ʾ��һ����������ϵͳ��ʱ��
	�Զ������÷���

	�����ڷ����ϵ���Ҽ���
		����
		��������
		ֹͣ����
		...
	
	�����Ըı�����Ĭ�����ã�
		�����ϵ���Ҽ������ԣ�Ȼ�����ѡ��������ʽ��
			�Զ����ӳ�������
			�Զ�
			�ֶ�
			����

5����windows����ϵͳ���У���ôʹ�������������͹ر�mysql�����أ�
	�﷨��
		net stop ��������;
		net start ��������;

	�����������ͣ�����Բ������ϵ����

6��mysql��װ�ˣ����������ˣ���ôʹ�ÿͻ��˵�¼mysql���ݿ��أ�
	**ʹ��binĿ¼�µ�mysql.exe����������mysql���ݿ������**

	���ص�¼����ʾ��д�������ʽ����
		C:\Users\Administrator>mysql -uroot -p123456
		Welcome to the MySQL monitor.  Commands end with ; or \g.
		Your MySQL connection id is 1
		Server version: 5.5.36 MySQL Community Server (GPL)
	
		Copyright (c) 2000, 2014, Oracle and/or its affiliates. All rights reserved.
	
		Oracle is a registered trademark of Oracle Corporation and/or its
		affiliates. Other names may be trademarks of their respective
		owners.
	
		Type 'help;' or '\h' for help. Type '\c' to clear the current input statement.
	
		mysql>


?	
?	
?	
	���䣺
	exit
	���˳�mysql������
	
	���ص�¼�������������ʽ����
		C:\Users\Administrator>mysql -uroot -p
		Enter password: ******
		Welcome to the MySQL monitor.  Commands end with ; or \g.
		Your MySQL connection id is 2
		Server version: 5.5.36 MySQL Community Server (GPL)
	
		Copyright (c) 2000, 2014, Oracle and/or its affiliates. All rights reserved.
	
		Oracle is a registered trademark of Oracle Corporation and/or its
		affiliates. Other names may be trademarks of their respective
		owners.
	
		Type 'help;' or '\h' for help. Type '\c' to clear the current input statement.
	
		mysql>

7��mysql�������

	�˳�mysql ��exit
	
	�鿴mysql������Щ���ݿ⣿
		show databases; 
		ע�⣺�ԷֺŽ�β���ֺ���Ӣ�ĵķֺš�
	
	mysql> show databases;
	+--------------------+
	| Database           |
	+--------------------+
	| information_schema |
	| mysql              |
	| performance_schema |
	| test               |
	+--------------------+
	mysqlĬ���Դ���4�����ݿ⡣
	
	��ôѡ��ʹ��ĳ�����ݿ��أ�
		mysql> use test;
		Database changed
		��ʾ����ʹ��һ�����ֽ���test�����ݿ⡣
	
	��ô�������ݿ��أ�
		mysql> create database bjpowernode;
		Query OK, 1 row affected (0.00 sec)
	
		mysql> show databases;
		+--------------------+
		| Database           |
		+--------------------+
		| information_schema |
		| bjpowernode        |
		| mysql              |
		| performance_schema |
		| test               |
		+--------------------+
	
	�鿴ĳ�����ݿ�������Щ��
		mysql> show tables;
	
	ע�⣺���ϵ�������ִ�Сд�����С�
	
	�鿴mysql���ݿ�(ָ�������exeӦ�ó���)�İ汾�ţ�
	mysql> select version();
		+-----------+
		| version() |
		+-----------+
		| 5.5.36    |
		+-----------+
	
	�鿴��ǰʹ�õ����ĸ����ݿ⣿
	mysql> select database();
	+-------------+
	| database()  |
	+-------------+
	| bjpowernode |
	+-------------+
	
	mysql> show
	-> databases
	-> ;
	+--------------------+
	| Database           |
	+--------------------+
	| information_schema |
	| bjpowernode        |
	| mysql              |
	| performance_schema |
	| test               |
	+--------------------+
	
	ע�⣺mysql�ǲ�����;����ִ�У���;����ʾ������������������������


?	
	mysql> show
	->
	->
	->
	->
	->
	->
	->
	->
	-> \c
	mysql>
	\c������ֹһ����������롣//ֻҪ����\c����ô����������Ч


8�����ݿ⵱��������ĵ�Ԫ�Ǳ�table

	ʲô�Ǳ�table��Ϊʲô�ñ����洢�����أ�
	
		����	�Ա�	����(�У��ֶ�) 
		---------------------------
		����	��			20            ------->�У���¼��
		����	Ů			21            ------->�У���¼��
		����	��			22            ------->�У���¼��
	
	���ݿ⵱�����Ա�����ʽ��ʾ���ݵġ�
	��Ϊ��Ƚ�ֱ�ۡ�
	
	����һ�����ݽṹ��ֻ��һ�ִ洢���ݵķ�ʽ
	
	�κ�һ�ű����к��У�
		�У�row��������Ϊ����/��¼��
		�У�column��������Ϊ�ֶΡ�
	
	�����ֶΡ��Ա��ֶΡ������ֶΡ�
	
	�˽�һ�£�
		ÿһ���ֶζ��У��ֶ������������͡�Լ�������ԡ�
		�ֶ���������⣬��һ����ͨ�����֣�����֪����С�
		�������ͣ��ַ��������֣����ڵȣ����ڽ���
	
		Լ����Լ��Ҳ�кܶ࣬����һ������Ψһ��Լ����
			����Լ�����֮�󣬸��ֶ��е����ݲ����ظ���

9������SQL���ķ��ࣿ

	SQL����кܶ࣬��ý��з��ű��࣬���������׼��䡣
		��Ϊ��
			DQL��
				���ݲ�ѯ���ԣ����Ǵ���select�ؼ��ֵĶ��ǲ�ѯ��䣩
				select...
	
			DML��
				���ݲ������ԣ����ǶԱ��е����ݽ�����ɾ�ĵĶ���DML��
				insert delete update
				insert ��
				delete ɾ
				update ��
	
				�����Ҫ�ǲ������е�����data��
				
				��i need u�����
	
			DDL��
				���ݶ�������
				���Ǵ���create��drop��alter�Ķ���DDL��
				DDL��Ҫ�������Ǳ�Ľṹ�����Ǳ��е����ݡ�
				create���½�����ͬ����
				drop��ɾ��
				alter���޸�
				�����ɾ�ĺ�DML��ͬ�������Ҫ�ǶԱ�ṹ���в�����
				
				��adc����� �������d ����b 
	
			TCL��
				�������Ƶ��ӡ�
				�������������
				������
					�����ύ��commit;
					����ع���rollback;
	
			DCL��
				�����ݿ������ԡ�
				���磺��Ȩgrant������Ȩ��revoke....


10������һ����ǰ׼���õ����ݣ�
	bjpowernode.sql ����ļ���������ǰΪ�����ϰ׼�������ݿ��
	��ô��sql�ļ��е����ݵ����أ�
		mysql> source D:\course\03-MySQL\document\bjpowernode.sql

		ע�⣺·���в�Ҫ�����ģ�������

11�����ڵ�����⼸�ű�
	mysql> show tables;
	+-----------------------+
	| Tables_in_bjpowernode |
	+-----------------------+
	| dept                  |
	| emp                   |
	| salgrade              |
	+-----------------------+

	dept�ǲ��ű�
	emp��Ա����
	salgrade �ǹ��ʵȼ���
	
	��ô�鿴���е������أ�
		select * from ����; //ͳһִ�����SQL��䡣
	
	mysql> select * from emp; // ��emp���ѯ�������ݡ�
	+-------+--------+-----------+------+------------+---------+---------+--------+
	| EMPNO | ENAME  | JOB       | MGR  | HIREDATE   | SAL     | COMM    | DEPTNO |
	+-------+--------+-----------+------+------------+---------+---------+--------+
	|  7369 | SMITH  | CLERK     | 7902 | 1980-12-17 |  800.00 |    NULL |     20 |
	|  7499 | ALLEN  | SALESMAN  | 7698 | 1981-02-20 | 1600.00 |  300.00 |     30 |
	|  7521 | WARD   | SALESMAN  | 7698 | 1981-02-22 | 1250.00 |  500.00 |     30 |
	|  7566 | JONES  | MANAGER   | 7839 | 1981-04-02 | 2975.00 |    NULL |     20 |
	|  7654 | MARTIN | SALESMAN  | 7698 | 1981-09-28 | 1250.00 | 1400.00 |     30 |
	|  7698 | BLAKE  | MANAGER   | 7839 | 1981-05-01 | 2850.00 |    NULL |     30 |
	|  7782 | CLARK  | MANAGER   | 7839 | 1981-06-09 | 2450.00 |    NULL |     10 |
	|  7788 | SCOTT  | ANALYST   | 7566 | 1987-04-19 | 3000.00 |    NULL |     20 |
	|  7839 | KING   | PRESIDENT | NULL | 1981-11-17 | 5000.00 |    NULL |     10 |
	|  7844 | TURNER | SALESMAN  | 7698 | 1981-09-08 | 1500.00 |    0.00 |     30 |
	|  7876 | ADAMS  | CLERK     | 7788 | 1987-05-23 | 1100.00 |    NULL |     20 |
	|  7900 | JAMES  | CLERK     | 7698 | 1981-12-03 |  950.00 |    NULL |     30 |
	|  7902 | FORD   | ANALYST   | 7566 | 1981-12-03 | 3000.00 |    NULL |     20 |
	|  7934 | MILLER | CLERK     | 7782 | 1982-01-23 | 1300.00 |    NULL |     10 |
	+-------+--------+-----------+------+------------+---------+---------+--------+
	
	mysql> select * from dept;
	+--------+------------+----------+
	| DEPTNO | DNAME      | LOC      |
	+--------+------------+----------+
	|     10 | ACCOUNTING | NEW YORK |
	|     20 | RESEARCH   | DALLAS   |
	|     30 | SALES      | CHICAGO  |
	|     40 | OPERATIONS | BOSTON   |
	+--------+------------+----------+
	
	mysql> select * from salgrade;
	+-------+-------+-------+
	| GRADE | LOSAL | HISAL |
	+-------+-------+-------+
	|     1 |   700 |  1200 |
	|     2 |  1201 |  1400 |
	|     3 |  1401 |  2000 |
	|     4 |  2001 |  3000 |
	|     5 |  3001 |  9999 |
	+-------+-------+-------+

12���������е����ݣ�ֻ����Ľṹ����һ�����
	desc ����;
mysql> desc dept;
+--------+-------------+------+-----+---------+-------+
| Field  | Type        | Null | Key | Default | Extra |
+--------+-------------+------+-----+---------+-------+
| DEPTNO | int(2)      | NO   | PRI | NULL    |       |���ű��
| DNAME  | varchar(14) | YES  |     | NULL    |       |��������
| LOC    | varchar(13) | YES  |     | NULL    |       |����λ��
+--------+-------------+------+-----+---------+-------+
mysql> desc emp;
+----------+-------------+------+-----+---------+-------+
| Field    | Type        | Null | Key | Default | Extra |
+----------+-------------+------+-----+---------+-------+
| EMPNO    | int(4)      | NO   | PRI | NULL    |       |Ա�����
| ENAME    | varchar(10) | YES  |     | NULL    |       |Ա������
| JOB      | varchar(9)  | YES  |     | NULL    |       |������λ
| MGR      | int(4)      | YES  |     | NULL    |       |�ϼ����
| HIREDATE | date        | YES  |     | NULL    |       |��ְ����
| SAL      | double(7,2) | YES  |     | NULL    |       |����
| COMM     | double(7,2) | YES  |     | NULL    |       |����
| DEPTNO   | int(2)      | YES  |     | NULL    |       |���ű��
+----------+-------------+------+-----+---------+-------+
mysql> desc salgrade;
+-------+---------+------+-----+---------+-------+
| Field | Type    | Null | Key | Default | Extra |
+-------+---------+------+-----+---------+-------+
| GRADE | int(11) | YES  |     | NULL    |       |���ʵȼ�
| LOSAL | int(11) | YES  |     | NULL    |       |��͹���
| HISAL | int(11) | YES  |     | NULL    |       |��߹���
+-------+---------+------+-----+---------+-------+

describe��дΪ��desc
mysql> describe dept;
+--------+-------------+------+-----+---------+-------+
| Field  | Type        | Null | Key | Default | Extra |
+--------+-------------+------+-----+---------+-------+
| DEPTNO | int(2)      | NO   | PRI | NULL    |       |
| DNAME  | varchar(14) | YES  |     | NULL    |       |
| LOC    | varchar(13) | YES  |     | NULL    |       |
+--------+-------------+------+-----+---------+-------+

13���򵥲�ѯ
	13.1����ѯһ���ֶΣ�
		select �ֶ��� from ����;
		����Ҫע�⣺
			select��from���ǹؼ��֡�
			�ֶ����ͱ������Ǳ�ʶ����
		

```markdown
	ǿ����
		����SQL�����˵����ͨ�õģ�
		���е�SQL����ԡ�;����β��
		����SQL��䲻���ִ�Сд�����С�
	
	��ѯ�������֣�
		mysql> select dname from dept;
		+------------+
		| dname      |
		+------------+
		| ACCOUNTING |
		| RESEARCH   |
		| SALES      |
		| OPERATIONS |
		+------------+
		4 rows in set (0.00 sec)

		mysql> SELECT DNAME FROM DEPT;
		+------------+
		| DNAME      |
		+------------+
		| ACCOUNTING |
		| RESEARCH   |
		| SALES      |
		| OPERATIONS |
		+------------+
		4 rows in set (0.00 sec)

13.2����ѯ�����ֶΣ����߶���ֶ���ô�죿
	ʹ�ö��Ÿ�����,��
	��ѯ���ű�źͲ�������
		select deptno,dname from dept;
		+--------+------------+
		| deptno | dname      |
		+--------+------------+
		|     10 | ACCOUNTING |
		|     20 | RESEARCH   |
		|     30 | SALES      |
		|     40 | OPERATIONS |
		+--------+------------+

13.3����ѯ�����ֶ���ô�죿

	��һ�ַ�ʽ�����԰�ÿ���ֶζ�д��
		select a,b,c,d,e,f... from tablename;

	�ڶ��ַ�ʽ������ʹ��*//��ѯ�����ֶξ��൱�ڲ�ѯ���е�������Ϣ
		select * from dept;
		+--------+------------+----------+
		| DEPTNO | DNAME      | LOC      |
		+--------+------------+----------+
		|     10 | ACCOUNTING | NEW YORK |
		|     20 | RESEARCH   | DALLAS   |
		|     30 | SALES      | CHICAGO  |
		|     40 | OPERATIONS | BOSTON   |
		+--------+------------+----------+

		���ַ�ʽ��ȱ�㣺
			1��Ч�ʵ�//��ò�Ҫ������д��д��java�У���Ϊ��java��*������Ҫת���������ֶε�����
			2���ɶ��Բ
		��ʵ�ʿ����в����飬�����Լ���û���⡣
		�������DOS�����������ٵĿ�һ��ȫ�����ݿ��Բ������ַ�ʽ��

13.4������ѯ�����������
	mysql> select deptno,dname as deptname from dept;
	+--------+------------+
	| deptno | deptname   |
	+--------+------------+
	|     10 | ACCOUNTING |
	|     20 | RESEARCH   |
	|     30 | SALES      |
	|     40 | OPERATIONS |
	+--------+------------+
	ʹ��as�ؼ����������
	ע�⣺ֻ�ǽ���ʾ�Ĳ�ѯ���������ʾΪdeptname��ԭ���������ǽУ�dname
	��ס��select�������Զ����������޸Ĳ����ġ�����Ϊֻ�����ѯ��

	as�ؼ��ֿ���ʡ���𣿿��Ե�
		mysql> select deptno,dname deptname from dept;
	
	�����������ʱ�򣬱��������пո���ô�죿
		mysql> select deptno,dname dept name from dept;
		DBMS������������䣬����SQL���ı��룬�������﷨�����뱨��
		��ô�����//SQL��������֮ǰҲ��Ҫ���������
		//�ֶ��� �� ��ʾ�������ֶ���֮����һ���ո����Ե�����������Ҳ�пո�Ļ���Ҫȥ��from �������Ҳ������Ա�����
			select deptno,dname 'dept name' from dept; //�ӵ�����
			select deptno,dname "dept name" from dept; //��˫����
			+--------+------------+
			| deptno | dept name  |
			+--------+------------+
			|     10 | ACCOUNTING |
			|     20 | RESEARCH   |
			|     30 | SALES      |
			|     40 | OPERATIONS |
			+--------+------------+
		
		ע�⣺�����е����ݿ⵱�У��ַ���ͳһʹ�õ�������������
		�������Ǳ�׼��˫������oracle���ݿ����ò��ˡ�������mysql
		�п���ʹ�á�

		�ٴ�ǿ�������ݿ��е��ַ������ǲ��õ����������������Ǳ�׼�ġ�
		˫���Ų���׼��

13.5������Ա����н��sal * 12
	mysql> select ename,sal from emp;
	+--------+---------+
	| ename  | sal     |
	+--------+---------+
	| SMITH  |  800.00 |
	| ALLEN  | 1600.00 |
	| WARD   | 1250.00 |
	| JONES  | 2975.00 |
	| MARTIN | 1250.00 |
	| BLAKE  | 2850.00 |
	| CLARK  | 2450.00 |
	| SCOTT  | 3000.00 |
	| KING   | 5000.00 |
	| TURNER | 1500.00 |
	| ADAMS  | 1100.00 |
	| JAMES  |  950.00 |
	| FORD   | 3000.00 |
	| MILLER | 1300.00 |
	+--------+---------+
	mysql> select ename,sal*12 from emp; // ���ۣ��ֶο���ʹ����ѧ���ʽ��
	+--------+----------+
	| ename  | sal*12   |
	+--------+----------+
	| SMITH  |  9600.00 |
	| ALLEN  | 19200.00 |
	| WARD   | 15000.00 |
	| JONES  | 35700.00 |
	| MARTIN | 15000.00 |
	| BLAKE  | 34200.00 |
	| CLARK  | 29400.00 |
	| SCOTT  | 36000.00 |
	| KING   | 60000.00 |
	| TURNER | 18000.00 |
	| ADAMS  | 13200.00 |
	| JAMES  | 11400.00 |
	| FORD   | 36000.00 |
	| MILLER | 15600.00 |
	+--------+----------+

	mysql> select ename,sal*12 as yearsal from emp; //�����
	+--------+----------+
	| ename  | yearsal  |
	+--------+----------+
	| SMITH  |  9600.00 |
	| ALLEN  | 19200.00 |
	| WARD   | 15000.00 |
	| JONES  | 35700.00 |
	| MARTIN | 15000.00 |
	| BLAKE  | 34200.00 |
	| CLARK  | 29400.00 |
	| SCOTT  | 36000.00 |
	| KING   | 60000.00 |
	| TURNER | 18000.00 |
	| ADAMS  | 13200.00 |
	| JAMES  | 11400.00 |
	| FORD   | 36000.00 |
	| MILLER | 15600.00 |
	+--------+----------+

	mysql> select ename,sal*12 as '��н' from emp; //���������ģ��õ�������������
	+--------+----------+
	| ename  | ��н        |
	+--------+----------+
	| SMITH  |  9600.00 |
	| ALLEN  | 19200.00 |
	| WARD   | 15000.00 |
	| JONES  | 35700.00 |
	| MARTIN | 15000.00 |
	| BLAKE  | 34200.00 |
	| CLARK  | 29400.00 |
	| SCOTT  | 36000.00 |
	| KING   | 60000.00 |
	| TURNER | 18000.00 |
	| ADAMS  | 13200.00 |
	| JAMES  | 11400.00 |
	| FORD   | 36000.00 |
	| MILLER | 15600.00 |
	+--------+----------+
```

14��������ѯ**//ɸѡ**

14.1��ʲô��������ѯ��
	���ǽ������������ݶ���������ǲ�ѯ�������������ġ�
	�﷨��ʽ��
		

```markdown
		select
			�ֶ�1,�ֶ�2,�ֶ�3....
		from 
			����
		where
			����;
```

14.2��������Щ������

```markdown
= ����
��ѯн�ʵ���800��Ա�������ͱ�ţ�
	select empno,ename from emp where sal = 800;
��ѯSMITH�ı�ź�н�ʣ�
	select empno,sal from emp where ename = 'SMITH'; //�ַ���ʹ�õ�����//��Ȼtable���õ��Ǵ�д����������Ҳ����дsmith����ΪSQL�ǲ����ִ�Сд��

<>��!= ������
��ѯн�ʲ�����800��Ա�������ͱ�ţ�
	select empno,ename from emp where sal != 800;
	select empno,ename from emp where sal <> 800; // С�ںźʹ��ں���ɵĲ��Ⱥ�

< С��
��ѯн��С��2000��Ա�������ͱ�ţ�
	mysql> select empno,ename,sal from emp where sal < 2000;
	+-------+--------+---------+
	| empno | ename  | sal     |
	+-------+--------+---------+
	|  7369 | SMITH  |  800.00 |
	|  7499 | ALLEN  | 1600.00 |
	|  7521 | WARD   | 1250.00 |
	|  7654 | MARTIN | 1250.00 |
	|  7844 | TURNER | 1500.00 |
	|  7876 | ADAMS  | 1100.00 |
	|  7900 | JAMES  |  950.00 |
	|  7934 | MILLER | 1300.00 |
	+-------+--------+---------+
```


	<= С�ڵ���
	��ѯн��С�ڵ���3000��Ա�������ͱ�ţ�
		select empno,ename,sal from emp where sal <= 3000;


```markdown
> ����
��ѯн�ʴ���3000��Ա�������ͱ�ţ�
	select empno,ename,sal from emp where sal > 3000;

>= ���ڵ���
��ѯн�ʴ��ڵ���3000��Ա�������ͱ�ţ�
	select empno,ename,sal from emp where sal >= 3000;

between �� and ��. ����ֵ֮��, ��ͬ�� >= and <=
��ѯн����2450��3000֮���Ա����Ϣ������2450��3000
	��һ�ַ�ʽ��>= and <= ��and�ǲ��ҵ���˼����
		select empno,ename,sal from emp where sal >= 2450 and sal <= 3000;
		select ename,sal,empno from emp where sal >=2450 and <=3000//����д���������������������������������
		+-------+-------+---------+
		| empno | ename | sal     |
		+-------+-------+---------+
		|  7566 | JONES | 2975.00 |
		|  7698 | BLAKE | 2850.00 |
		|  7782 | CLARK | 2450.00 |
		|  7788 | SCOTT | 3000.00 |
		|  7902 | FORD  | 3000.00 |
		+-------+-------+---------+
	�ڶ��ַ�ʽ��between �� and ��
		select 
			empno,ename,sal 
		from 
			emp 
		where 
			sal between 2450 and 3000;
		
		ע�⣺
			ʹ��between and��ʱ�򣬱�����ѭ��С�Ҵ�
			between and�Ǳ����䣬�������˵�ֵ��

is null Ϊ null��is not null ��Ϊ�գ�
��ѯ��ЩԱ���Ľ���/����Ϊnull��
	mysql> select empno,ename,sal,comm from emp where comm = null;//����д���������������������������������
	Empty set (0.00 sec)

	mysql> select empno,ename,sal,comm from emp where comm is null;
	+-------+--------+---------+------+
	| empno | ename  | sal     | comm |
	+-------+--------+---------+------+
	|  7369 | SMITH  |  800.00 | NULL |
	|  7566 | JONES  | 2975.00 | NULL |
	|  7698 | BLAKE  | 2850.00 | NULL |
	|  7782 | CLARK  | 2450.00 | NULL |
	|  7788 | SCOTT  | 3000.00 | NULL |
	|  7839 | KING   | 5000.00 | NULL |
	|  7876 | ADAMS  | 1100.00 | NULL |
	|  7900 | JAMES  |  950.00 | NULL |
	|  7902 | FORD   | 3000.00 | NULL |
	|  7934 | MILLER | 1300.00 | NULL |
	+-------+--------+---------+------+
	10 rows in set (0.00 sec)

	ע�⣺�����ݿ⵱��null����ʹ�õȺŽ��к�������Ҫʹ��is null
	��Ϊ���ݿ��е�null����ʲôҲû�У�������һ��ֵ�����Բ���ʹ��
	�Ⱥź�����
	null�����ݿ��д���Ϊ�գ�Ϊ�յĻ��Ͳ�����=���к�����ֻ�е���ֵ��ʱ����õȺŽ��к���

��ѯ��ЩԱ���Ľ���/������Ϊnull��
	select empno,ename,sal,comm from emp where comm is not null;
	+-------+--------+---------+---------+
	| empno | ename  | sal     | comm    |
	+-------+--------+---------+---------+
	|  7499 | ALLEN  | 1600.00 |  300.00 |
	|  7521 | WARD   | 1250.00 |  500.00 |
	|  7654 | MARTIN | 1250.00 | 1400.00 |
	|  7844 | TURNER | 1500.00 |    0.00 |
	+-------+--------+---------+---------+

and ����
��ѯ������λ��MANAGER���ҹ��ʴ���2500��Ա����Ϣ��
	select 
		empno,ename,job,sal 
	from 
		emp 
	where 
		job = 'MANAGER' and sal > 2500;
	
	+-------+-------+---------+---------+
	| empno | ename | job     | sal     |
	+-------+-------+---------+---------+
	|  7566 | JONES | MANAGER | 2975.00 |
	|  7698 | BLAKE | MANAGER | 2850.00 |
	+-------+-------+---------+---------+

or ����
��ѯ������λ��MANAGER��SALESMAN��Ա����
	select empno,ename,job from emp where job = 'MANAGER';
	select empno,ename,job from emp where job = 'SALESMAN';

	select 
		empno,ename,job
	from
		emp
	where 
		job = 'MANAGER' or job = 'SALESMAN';

	+-------+--------+----------+
	| empno | ename  | job      |
	+-------+--------+----------+
	|  7499 | ALLEN  | SALESMAN |
	|  7521 | WARD   | SALESMAN |
	|  7566 | JONES  | MANAGER  |
	|  7654 | MARTIN | SALESMAN |
	|  7698 | BLAKE  | MANAGER  |
	|  7782 | CLARK  | MANAGER  |
	|  7844 | TURNER | SALESMAN |
	+-------+--------+----------+

and��orͬʱ���ֵĻ��������ȼ�������
��ѯ���ʴ���2500�����Ҳ��ű��Ϊ10��20���ŵ�Ա����
	select 
		*
	from
		emp
	where
		sal > 2500 and deptno = 10 or deptno = 20;
	���������������⣿
		and���ȼ���or�ߡ�
		����������ִ��and��Ȼ��ִ��or��
		�����������ʾʲô���壿
			�ҳ����ʴ���2500���Ҳ��ű��Ϊ10��Ա��������20��������Ա���ҳ�����
	
	select 
		*
	from
		emp
	where
		sal > 2500 and (deptno = 10 or deptno = 20);
	
	and��orͬʱ���֣�and���ȼ��ϸߡ��������or��ִ�У���Ҫ�ӡ�С���š�
	�Ժ��ڿ����У������ȷ�����ȼ����ͼ�С���ž����ˡ�

in �������൱�ڶ�� or ��not in ���������Χ�У�
	��ѯ������λ��MANAGER��SALESMAN��Ա����
		select empno,ename,job from emp where job = 'MANAGER' or job = 'SALESMAN';
		select empno,ename,job from emp where job in('MANAGER', 'SALESMAN');
		+-------+--------+----------+
		| empno | ename  | job      |
		+-------+--------+----------+
		|  7499 | ALLEN  | SALESMAN |
		|  7521 | WARD   | SALESMAN |
		|  7566 | JONES  | MANAGER  |
		|  7654 | MARTIN | SALESMAN |
		|  7698 | BLAKE  | MANAGER  |
		|  7782 | CLARK  | MANAGER  |
		|  7844 | TURNER | SALESMAN |
		+-------+--------+----------+
		ע�⣺in����һ�����䡣in��������Ǿ����ֵ��

	��ѯн����800��5000��Ա����Ϣ��
		select ename,sal from emp where sal = 800 or sal = 5000;
		select ename,sal from emp where sal in(800, 5000); //������Ǳ�ʾ800��5000���ҳ�����
		+-------+---------+
		| ename | sal     |
		+-------+---------+
		| SMITH |  800.00 |
		| KING  | 5000.00 |
		+-------+---------+
		select ename,sal from emp where sal in(800, 5000, 3000);

		// not in ��ʾ�����⼸��ֵ���е����ݡ�
		select ename,sal from emp where sal not in(800, 5000, 3000);
		+--------+---------+
		| ename  | sal     |
		+--------+---------+
		| ALLEN  | 1600.00 |
		| WARD   | 1250.00 |
		| JONES  | 2975.00 |
		| MARTIN | 1250.00 |
		| BLAKE  | 2850.00 |
		| CLARK  | 2450.00 |
		| TURNER | 1500.00 |
		| ADAMS  | 1100.00 |
		| JAMES  |  950.00 |
		| MILLER | 1300.00 |
		+--------+---------+

not ����ȡ�ǣ���Ҫ���� is �� in ��
	is null
	is not null
	in
	not in

like 
	��Ϊģ����ѯ��֧��%���»���ƥ��
	%ƥ���������ַ�
	�»��ߣ�����һ���ַ���
	
	��%��һ������ķ��ţ�_ Ҳ��һ��������ţ�
	
	%��ʾ�������ַ�
	_��ʾ����һ���ַ�

	�ҳ������к���O�ģ�
	mysql> select ename from emp where ename like '%O%';
	+-------+
	| ename |
	+-------+
	| JONES |
	| SCOTT |
	| FORD  |
	+-------+

	�ҳ�������T��β�ģ�
		select ename from emp where ename like '%T';
		
	�ҳ�������K��ʼ�ģ�
		select ename from emp where ename like 'K%';

	�ҳ��ڶ�����ÿ��A�ģ�
		select ename from emp where ename like '_A%';
	
	�ҳ���������ĸ��R�ģ�
		select ename from emp where ename like '__R%';
	
	t_studentѧ����
	name�ֶ�
	----------------------
	zhangsan
	lisi
	wangwu
	zhaoliu
	jack_son

	�ҳ��������С�_���ģ�
		select name from t_student where name like '%_%'; //�������С�

		mysql> select name from t_student where name like '%\_%'; // \ת���ַ���
		+----------+
		| name     |
		+----------+
		| jack_son |
		+----------+
```

15������

15.1����ѯ����Ա��н�ʣ�����
	select 
		ename,sal
	from
		emp
	order by
		sal; // Ĭ�������򣡣���

	+--------+---------+
	| ename  | sal     |
	+--------+---------+
	| SMITH  |  800.00 |
	| JAMES  |  950.00 |
	| ADAMS  | 1100.00 |
	| WARD   | 1250.00 |
	| MARTIN | 1250.00 |
	| MILLER | 1300.00 |
	| TURNER | 1500.00 |
	| ALLEN  | 1600.00 |
	| CLARK  | 2450.00 |
	| BLAKE  | 2850.00 |
	| JONES  | 2975.00 |
	| FORD   | 3000.00 |
	| SCOTT  | 3000.00 |
	| KING   | 5000.00 |
	+--------+---------+

15.2����ô����

```markdown
ָ������
select 
	ename,sal
from
	emp
order by
	sal desc;//descend�½�
```

+--------+---------+
| ename  | sal     |
+--------+---------+
| KING   | 5000.00 |
| SCOTT  | 3000.00 |
| FORD   | 3000.00 |
| JONES  | 2975.00 |
| BLAKE  | 2850.00 |
| CLARK  | 2450.00 |
| ALLEN  | 1600.00 |
| TURNER | 1500.00 |
| MILLER | 1300.00 |
| MARTIN | 1250.00 |
| WARD   | 1250.00 |
| ADAMS  | 1100.00 |
| JAMES  |  950.00 |
| SMITH  |  800.00 |
+--------+---------+

```markdown
ָ������
select 
	ename,sal
from
	emp
order by
	sal asc;//ascend ����
```

+--------+---------+
| ename  | sal     |
+--------+---------+
| SMITH  |  800.00 |
| JAMES  |  950.00 |
| ADAMS  | 1100.00 |
| WARD   | 1250.00 |
| MARTIN | 1250.00 |
| MILLER | 1300.00 |
| TURNER | 1500.00 |
| ALLEN  | 1600.00 |
| CLARK  | 2450.00 |
| BLAKE  | 2850.00 |
| JONES  | 2975.00 |
| FORD   | 3000.00 |
| SCOTT  | 3000.00 |
| KING   | 5000.00 |
+--------+---------+

15.3�����������ֶ������𣿻���˵���ն���ֶ�����
	��ѯԱ�����ֺ�н�ʣ�Ҫ����н���������н��һ���Ļ���
	�ٰ��������������С�
	select 
		ename,sal
	from
		emp
	order by
		sal asc, ename asc; // **sal��ǰ����������ֻ��sal��ȵ�ʱ�򣬲Żῼ������ename����**

	+--------+---------+
	| ename  | sal     |
	+--------+---------+
	| SMITH  |  800.00 |
	| JAMES  |  950.00 |
	| ADAMS  | 1100.00 |
	| MARTIN | 1250.00 |
	| WARD   | 1250.00 |
	| MILLER | 1300.00 |
	| TURNER | 1500.00 |
	| ALLEN  | 1600.00 |
	| CLARK  | 2450.00 |
	| BLAKE  | 2850.00 |
	| JONES  | 2975.00 |
	| FORD   | 3000.00 |
	| SCOTT  | 3000.00 |
	| KING   | 5000.00 |
	+--------+---------+

15.4���˽⣺�����ֶε�λ��Ҳ��������
	select ename,sal from emp order by 2; // 2��ʾ�ڶ��С��ڶ�����sal
	**���ղ�ѯ����ĵ�2��sal����**

	�˽�һ�£��������ڿ���������д����Ϊ����׳��
	��Ϊ�е�˳������׷����ı䣬��˳���޸�֮��2�ͷ��ˡ�

16���ۺ�һ��İ�����**//��ɸѡ��������**
	�ҳ�������1250��3000֮���Ա����Ϣ��Ҫ����н�ʽ������С�
	select 
		ename,sal
	from
		emp
	where
		sal between 1250 and 3000
	order by
		sal desc;

+--------+---------+
| ename  | sal     |
+--------+---------+
| FORD   | 3000.00 |
| SCOTT  | 3000.00 |
| JONES  | 2975.00 |
| BLAKE  | 2850.00 |
| CLARK  | 2450.00 |
| ALLEN  | 1600.00 |
| TURNER | 1500.00 |
| MILLER | 1300.00 |
| MARTIN | 1250.00 |
| WARD   | 1250.00 |
+--------+---------+
	
	�ؼ���˳���ܱ䣺
		select
			...
		from
			...
		where
			...
		order by
			...
		
		��������ִ��˳��������գ�
			��һ����from
			�ڶ�����where
			��������select
			���Ĳ���order by���������������ִ�У���

# 17�����ݴ�����

17.1�����ݴ������ֱ���Ϊ**���д�����**//һ��һ�еĴ���һ�������Ӧһ�����  //һ��һ�� һ����¼һ����¼�Ĵ���һ����¼�������˲�ȥ������һ����¼��

//**���д�����**�����麯��������//һ���ֶε� ����

	���д��������ص㣺һ�������Ӧһ�������
	
	�͵��д�������Ե��ǣ����д������������д������ص㣺������룬��Ӧ1���������

17.2�����д���������������Щ��

```markdown
lower ת��Сд
	mysql> select lower(ename) as ename from emp;
	+--------+
	| ename  |
	+--------+
	| smith  |
	| allen  |
	| ward   |
	| jones  |
	| martin |
	| blake  |
	| clark  |
	| scott  |
	| king   |
	| turner |
	| adams  |
	| james  |
	| ford   |
	| miller |
	+--------+
	14�����룬�����14����������ǵ��д��������ص㡣

upper ת����д
	mysql> select * from t_student;
	+----------+
	| name     |
	+----------+
	| zhangsan |
	| lisi     |
	| wangwu   |
	| jack_son |
	+----------+

	mysql> select upper(name) as name from t_student;
	+----------+
	| name     |
	+----------+
	| ZHANGSAN |
	| LISI     |
	| WANGWU   |
	| JACK_SON |
	+----------+

substr ȡ�Ӵ���substr( ����ȡ���ַ���, ��ʼ�±�,��ȡ�ĳ���)��
	select substr(ename, 1, 1) as ename from emp;
	ע�⣺��ʼ�±��1��ʼ��û��0.
	�ҳ�Ա�����ֵ�һ����ĸ��A��Ա����Ϣ��
		��һ�ַ�ʽ��ģ����ѯ
			select ename from emp where ename like 'A%';
		�ڶ��ַ�ʽ��substr����
			select 
				ename 
			from 
				emp 
			where 
				substr(ename,1,1) = 'A';

	����ĸ��д��
		select name from t_student;
		select upper(substr(name,1,1)) from t_student;
		select substr(name,2,length(name) - 1) from t_student;
		select concat(upper(substr(name,1,1)),substr(name,2,length(name) - 1)) as 
		
		
�ַ���ƴ�ӣ�
������JAVAһ��ֱ�����
����Ҫ��concat(,)�������ַ���ƴ��������������������������������������������������
		
		
		result from t_student;
		+----------+
		| result   |
		+----------+
		| Zhangsan |
		| Lisi     |
		| Wangwu   |
		| Jack_son |
		+----------+
	
concat���������ַ�����ƴ��
	select concat(empno,ename) from emp;
	+---------------------+
	| concat(empno,ename) |
	+---------------------+
	| 7369SMITH           |
	| 7499ALLEN           |
	| 7521WARD            |
	| 7566JONES           |
	| 7654MARTIN          |
	| 7698BLAKE           |
	| 7782CLARK           |
	| 7788SCOTT           |
	| 7839KING            |
	| 7844TURNER          |
	| 7876ADAMS           |
	| 7900JAMES           |
	| 7902FORD            |
	| 7934MILLER          |
	+---------------------+

length ȡ����
	select length(ename) enamelength from emp;
	+-------------+
	| enamelength |
	+-------------+
	|           5 |
	|           5 |
	|           4 |
	|           5 |
	|           6 |
	|           5 |
	|           5 |
	|           5 |
	|           4 |
	|           6 |
	|           5 |
	|           5 |
	|           4 |
	|           6 |
	+-------------+

trim ȥ�ո�//ȥ��ǰ��Ŀո�
	mysql> select * from emp where ename = '  KING';
	Empty set (0.00 sec)

	mysql> select * from emp where ename = trim('   KING');
	+-------+-------+-----------+------+------------+---------+------+--------+
	| EMPNO | ENAME | JOB       | MGR  | HIREDATE   | SAL     | COMM | DEPTNO |
	+-------+-------+-----------+------+------------+---------+------+--------+
	|  7839 | KING  | PRESIDENT | NULL | 1981-11-17 | 5000.00 | NULL |     10 |
	+-------+-------+-----------+------+------------+---------+------+--------+
	
	
	
	
	//�㿴����ĵ��д��������������ں������ĺ�����˸�С����

str_to_date ���ַ���ת��������
date_format ��ʽ������
format ����ǧ��λ

case..when..then..when..then..else..end//��ʲôʱ����ô������ʲôʱ����ô�����������������������ô��
	��Ա���Ĺ�����λ��MANAGER��ʱ�򣬹����ϵ�10%����������λ��SALESMAN��ʱ�򣬹����ϵ�50%,����������
	��ע�⣺���޸����ݿ⣬ֻ�ǽ���ѯ�����ʾΪ�����ϵ���
	select 
		ename,
		job, 
		sal as oldsal,
		(case job when 'MANAGER' then sal*1.1 when 'SALESMAN' then sal*1.5 else sal end) as newsal 
	from 
		emp;
	
	+--------+-----------+---------+---------+
	| ename  | job       | oldsal  | newsal  |
	+--------+-----------+---------+---------+
	| SMITH  | CLERK     |  800.00 |  800.00 |
	| ALLEN  | SALESMAN  | 1600.00 | 2400.00 |
	| WARD   | SALESMAN  | 1250.00 | 1875.00 |
	| JONES  | MANAGER   | 2975.00 | 3272.50 |
	| MARTIN | SALESMAN  | 1250.00 | 1875.00 |
	| BLAKE  | MANAGER   | 2850.00 | 3135.00 |
	| CLARK  | MANAGER   | 2450.00 | 2695.00 |
	| SCOTT  | ANALYST   | 3000.00 | 3000.00 |
	| KING   | PRESIDENT | 5000.00 | 5000.00 |
	| TURNER | SALESMAN  | 1500.00 | 2250.00 |
	| ADAMS  | CLERK     | 1100.00 | 1100.00 |
	| JAMES  | CLERK     |  950.00 |  950.00 |
	| FORD   | ANALYST   | 3000.00 | 3000.00 |
	| MILLER | CLERK     | 1300.00 | 1300.00 |
	+--------+-----------+---------+---------+

round ��������
	select �ֶ� from ����;
	select ename from emp;
	select 'abc' from emp; // select����ֱ�Ӹ���������/����ֵ��
	//����ֱ��д�� select abc from emp;��Ϊ���select����ĵ������ֶ�������table��û������ֶ������Իᱨ��

	mysql> select 'abc' as bieming from emp;
	+---------+
	| bieming |
	+---------+
	| abc     |
	| abc     |
	| abc     |
	| abc     |
	| abc     |
	| abc     |
	| abc     |
	| abc     |
	| abc     |
	| abc     |
	| abc     |
	| abc     |
	| abc     |
	| abc     |
	+---------+

	mysql> select abc from emp;
	ERROR 1054 (42S22): Unknown column 'abc' in 'field list'
	�����϶�������Ϊ���abc����һ���ֶε����֣�ȥemp������abc�ֶ�ȥ�ˡ�

	select 1000 as num from emp; // 1000 Ҳ�Ǳ�����һ��������/����ֵ��
	+------+
	| num  |
	+------+
	| 1000 |
	| 1000 |
	| 1000 |
	| 1000 |
	| 1000 |
	| 1000 |
	| 1000 |
	| 1000 |
	| 1000 |
	| 1000 |
	| 1000 |
	| 1000 |
	| 1000 |
	| 1000 |
	+------+
	select 1000 from emp; // 1000 Ҳ�Ǳ�����һ��������/����ֵ��
	+------+
	| 1000 |
	+------+
	| 1000 |
	| 1000 |
	| 1000 |
	| 1000 |
	| 1000 |
	| 1000 |
	| 1000 |
	| 1000 |
	| 1000 |
	| 1000 |
	| 1000 |
	| 1000 |
	| 1000 |
	| 1000 |
	+------+
	
	select 21000 as num from dept;
	+-------+
	| num   |
	+-------+
	| 21000 |
	| 21000 |
	| 21000 |
	| 21000 |
	+-------+
	
	���ۣ�select������Ը�ĳ������ֶ��������Ե�ͬ��������������Ҳ���Ը�������/����ֵ�����ݣ���
	�����������/����ֵ���������ݣ� ��ô���ݿ�ͻ���ݱ�������Զ��������չʾ����
	

	mysql> select round(1236.567, 0) as result from emp; //�������롣��������λ��
	+--------+
	| result |
	+--------+
	|   1237 |
	|   1237 |
	|   1237 |
	|   1237 |
	|   1237 |
	|   1237 |
	|   1237 |
	|   1237 |
	|   1237 |
	|   1237 |
	|   1237 |
	|   1237 |
	|   1237 |
	|   1237 |
	+--------+

	select round(1236.567, 1) as result from emp; //����1��С��
	select round(1236.567, 2) as result from emp; //����2��С��
	select round(1236.567, -1) as result from emp; // ������ʮλ��
	+--------+
	| result |
	+--------+
	|   1240 |
	|   1240 |
	|   1240 |
	|   1240 |
	|   1240 |
	|   1240 |
	|   1240 |
	|   1240 |
	|   1240 |
	|   1240 |
	|   1240 |
	|   1240 |
	|   1240 |
	|   1240 |
	+--------+

	select round(1236.567, -2) as result from emp;//�������룬��������λ
	+--------+
	| result |
	+--------+
	|   1200 |
	|   1200 |
	|   1200 |
	|   1200 |
	|   1200 |
	|   1200 |
	|   1200 |
	|   1200 |
	|   1200 |
	|   1200 |
	|   1200 |
	|   1200 |
	|   1200 |
	|   1200 |
	+--------+

rand() ���������//���д����� ��Χ[0,1)
	mysql> select round(rand()*100,0) from emp; // 100���ڵ������
	+---------------------+
	| round(rand()*100,0) |
	+---------------------+
	|                  76 |
	|                  29 |
	|                  15 |
	|                  88 |
	|                  95 |
	|                   9 |
	|                  63 |
	|                  89 |
	|                  54 |
	|                   3 |
	|                  54 |
	|                  61 |
	|                  42 |
	|                  28 |
	+---------------------+
	
ifnull ���Խ� null ת����һ������ֵ
	ifnull�ǿմ�������ר�Ŵ���յġ�
	���������ݿ⵱�У�ֻҪ��NULL�������ѧ���㣬���ս������NULL��
	mysql> select ename, sal + comm as salcomm from emp;
	+--------+---------+
	| ename  | salcomm |
	+--------+---------+
	| SMITH  |    NULL |
	| ALLEN  | 1900.00 |
	| WARD   | 1750.00 |
	| JONES  |    NULL |
	| MARTIN | 2650.00 |
	| BLAKE  |    NULL |
	| CLARK  |    NULL |
	| SCOTT  |    NULL |
	| KING   |    NULL |
	| TURNER | 1500.00 |
	| ADAMS  |    NULL |
	| JAMES  |    NULL |
	| FORD   |    NULL |
	| MILLER |    NULL |
	+--------+---------+

	����ÿ��Ա������н��
		��н = (��н + �²���) * 12
		
		select ename, (sal + comm) * 12 as yearsal from emp;
		+--------+----------+
		| ename  | yearsal  |
		+--------+----------+
		| SMITH  |     NULL |
		| ALLEN  | 22800.00 |
		| WARD   | 21000.00 |
		| JONES  |     NULL |
		| MARTIN | 31800.00 |
		| BLAKE  |     NULL |
		| CLARK  |     NULL |
		| SCOTT  |     NULL |
		| KING   |     NULL |
		| TURNER | 18000.00 |
		| ADAMS  |     NULL |
		| JAMES  |     NULL |
		| FORD   |     NULL |
		| MILLER |     NULL |
		+--------+----------+

		ע�⣺NULLֻҪ�������㣬���ս��һ����NULL��Ϊ�˱������������Ҫʹ��ifnull������
		ifnull�����÷���ifnull(����, �������ĸ�ֵ)
			��������ݡ�ΪNULL��ʱ�򣬰�������ݽṹ�����ĸ�ֵ��
		
		����ΪNULL��ʱ�򣬽���������0
			select ename, (sal + ifnull(comm, 0)) * 12 as yearsal from emp;
			+--------+----------+
			| ename  | yearsal  |
			+--------+----------+
			| SMITH  |  9600.00 |
			| ALLEN  | 22800.00 |
			| WARD   | 21000.00 |
			| JONES  | 35700.00 |
			| MARTIN | 31800.00 |
			| BLAKE  | 34200.00 |
			| CLARK  | 29400.00 |
			| SCOTT  | 36000.00 |
			| KING   | 60000.00 |
			| TURNER | 18000.00 |
			| ADAMS  | 13200.00 |
			| JAMES  | 11400.00 |
			| FORD   | 36000.00 |
			| MILLER | 15600.00 |
			+--------+----------+
```

# 18�����麯�������д�������//һ���е�ȥ����//�����������������麯����ʹ�õ�ʱ���Զ�����null������Ҫ��null���д���count��ʱ������null�൱��û��ֱ���������������麯��Ҳ��һ���ġ����������������

```markdown
���д��������ص㣺������У��������һ�С�

5����
	count	����
	sum	���
	avg	ƽ��ֵ
	max	���ֵ
	min	��Сֵ

ע�⣺
	���麯����ʹ�õ�ʱ������Ƚ��з��飬Ȼ������á�
	�����û�ж����ݽ��з��飬���ű�Ĭ��Ϊһ�顣

�ҳ���߹��ʣ�
	mysql> select max(sal) from emp;
	+----------+
	| max(sal) |
	+----------+
	|  5000.00 |
	+----------+

�ҳ���͹��ʣ�
	mysql> select min(sal) from emp;
	+----------+
	| min(sal) |
	+----------+
	|   800.00 |
	+----------+

���㹤�ʺͣ�
	mysql> select sum(sal) from emp;
	+----------+
	| sum(sal) |
	+----------+
	| 29025.00 |
	+----------+

����ƽ�����ʣ�
	mysql> select avg(sal) from emp;
	+-------------+
	| avg(sal)    |
	+-------------+
	| 2073.214286 |
	+-------------+
	14������ȫ����������Ȼ�����14��

����Ա��������
	mysql> select count(ename) from emp;
	+--------------+
	| count(ename) |
	+--------------+
	|           14 |
	+--------------+

���麯����ʹ�õ�ʱ����Ҫע����Щ��

	��һ�㣺���麯���Զ�����NULL���㲻��Ҫ��ǰ��NULL���д���
	mysql> select sum(comm) from emp;
	+-----------+
	| sum(comm) |
	+-----------+
	|   2200.00 |
	+-----------+
	
	mysql> select count(comm) from emp;
	+-------------+
	| count(comm) |
	+-------------+
	|           4 |
	+-------------+
	mysql> select avg(comm) from emp;
	+------------+
	| avg(comm)  |
	+------------+
	| 550.000000 |
	+------------+

	�ڶ��㣺���麯����count(*)��count(�����ֶ�)��ʲô����
		mysql> select count(*) from emp;
		+----------+
		| count(*) |
		+----------+
		|       14 |
		+----------+

		mysql> select count(comm) from emp;
		+-------------+
		| count(comm) |
		+-------------+
		|           4 |
		+-------------+

		count(�����ֶ�)����ʾͳ�Ƹ��ֶ������в�ΪNULL��Ԫ�ص�������
		count(*)��ͳ�Ʊ��е�����������ֻҪ��һ������count��++��
					��Ϊÿһ�м�¼�����ܶ�ΪNULL��һ����������һ�в�ΪNULL�����������ݾ�����Ч�ġ�
����������������ݿ��У�ֻҪһ���Ǵ��ڵģ�����һ�е������ֶ��У�������һ���ֶβ�Ϊnull����������������������������������������������
	
	�����㣺���麯�����ܹ�ֱ��ʹ����where�Ӿ��С�
		�ҳ�����͹��ʸߵ�Ա����Ϣ��
			select ename,sal from emp where sal > min(sal);
			������û���⣬����һ�£�
				ERROR 1111 (HY000): Invalid use of group function
	?????????????????????????????????????????????????????????????????????
		˵������ѯ(group by)֮����������ˡ�

	���ĵ㣺���еķ��麯�������������һ���á�
		select sum(sal),min(sal),max(sal),avg(sal),count(*) from emp;
		+----------+----------+----------+-------------+----------+
		| sum(sal) | min(sal) | max(sal) | avg(sal)    | count(*) |
		+----------+----------+----------+-------------+----------+
		| 29025.00 |   800.00 |  5000.00 | 2073.214286 |       14 |
		+----------+----------+----------+-------------+----------+
```

# 19�������ѯ���ǳ���Ҫ�������*****��//���Ļ���һЩ����ϸ�ڵĽ���

```markdown
19.1��ʲô�Ƿ����ѯ��
	��ʵ�ʵ�Ӧ���У�������������������Ҫ�Ƚ��з��飬Ȼ���ÿһ������ݽ��в�����
	���ʱ��������Ҫʹ�÷����ѯ����ô���з����ѯ�أ�
		select
			...
		from
			...
		group by
			...
		
		����ÿ�����ŵĹ��ʺͣ�
		����ÿ��������λ��ƽ��н�ʣ�
		�ҳ�ÿ��������λ�����н�ʣ�
		....

19.2����֮ǰ�Ĺؼ���ȫ�������һ������һ�����ǵ�ִ��˳��
	select
		...
	from
		...
	where
		...
	group by
		...
	order by
		...
	
	���Ϲؼ��ֵ�˳���ܵߵ�����Ҫ���䡣
	ִ��˳����ʲô��
		1. from//�ñ�
		2. where//����
		3. group by//����
		4. select//ѡ������
		5. order by//����
	
	Ϊʲô���麯������ֱ��ʹ����where���棿
		select ename,sal from emp where sal > min(sal);//����
		��Ϊ���麯����ʹ�õ�ʱ������ȷ���֮�����ʹ�á�
		whereִ�е�ʱ�򣬻�û�з��顣����where���治�ܳ��ַ��麯����

		select sum(sal) from emp; 
		����������൱��select sum(sal) from emp group by ���ű�;
		���û�з��飬Ϊɶsum()�����������أ�
			��Ϊselect��group by֮��ִ�С�
		
19.3���ҳ�ÿ��������λ�Ĺ��ʺͣ�

	ʵ��˼·�����չ�����λ���飬Ȼ��Թ�����͡�
		select 
			job,sum(sal)
		from
			emp
		group by
			job;
		
		+-----------+----------+
		| job       | sum(sal) |
		+-----------+----------+
		| ANALYST   |  6000.00 |
		| CLERK     |  4150.00 |
		| MANAGER   |  8275.00 |
		| PRESIDENT |  5000.00 |
		| SALESMAN  |  5600.00 |
		+-----------+----------+
		�����������ִ��˳��
			�ȴ�emp���в�ѯ���ݡ�
			����job�ֶν��з��顣
			Ȼ���ÿһ������ݽ���sum(sal)
	
	select ename,job,sum(sal) from emp group by job;
	+-------+-----------+----------+
	| ename | job       | sum(sal) |
	+-------+-----------+----------+
	| SCOTT | ANALYST   |  6000.00 |
	| SMITH | CLERK     |  4150.00 |
	| JONES | MANAGER   |  8275.00 |
	| KING  | PRESIDENT |  5000.00 |
	| ALLEN | SALESMAN  |  5600.00 |
	+-------+-----------+----------+
	����ǰ���ename����ȫû�������
	���������mysql�п���ִ�У����Ǻ������塣
	//������д��ֻ���ڲ�ʹ�÷��麯���������Ǽ򵥵ĸ���ĳ���������������˵�����壨�����ķ���չʾ�����Ľ������Ƿ����еĵ�һ�����ݼ�¼��
	���ʹ���˷��麯��������ĳ���ֶε����ݣ��������Ļ���ȫ�����Ӧ����
    �����������﷨��ORACLE�и����в�ͨ
    
	
	���������oracle��ִ�б���
	oracle���﷨��mysql���﷨�ϸ񡣣�mysql���﷨�����˵��ɢһЩ����

	�ص���ۣ�
		��һ��select��䵱�У������group by���Ļ���
		select����ֻ�ܸ����μӷ�����ֶΣ��Լ����麯����
		������һ�ɲ��ܸ���

19.4���ҳ�ÿ�����ŵ����н��
	ʵ��˼·��ʲô��
		���ղ��ű�ŷ��飬��ÿһ������ֵ��

		select�������ename�ֶ�û�����壬����oracle�ᱨ��
		mysql> select ename,deptno,max(sal) from emp group by deptno;
		+-------+--------+----------+
		| ename | deptno | max(sal) |
		+-------+--------+----------+
		| CLARK |     10 |  5000.00 |
		| SMITH |     20 |  3000.00 |
		| ALLEN |     30 |  2850.00 |
		+-------+--------+----------+

		mysql> select deptno,max(sal) from emp group by deptno;
		+--------+----------+
		| deptno | max(sal) |
		+--------+----------+
		|     10 |  5000.00 |
		|     20 |  3000.00 |
		|     30 |  2850.00 |
		+--------+----------+

19.5���ҳ���ÿ�����ţ���ͬ������λ�������н�ʣ�
	+--------+-----------+---------+--------+
	| ename  | job       | sal     | deptno |
	+--------+-----------+---------+--------+
	| MILLER | CLERK     | 1300.00 |     10 |
	| KING   | PRESIDENT | 5000.00 |     10 |
	| CLARK  | MANAGER   | 2450.00 |     10 |

	| FORD   | ANALYST   | 3000.00 |     20 |
	| ADAMS  | CLERK     | 1100.00 |     20 |
	| SCOTT  | ANALYST   | 3000.00 |     20 |
	| JONES  | MANAGER   | 2975.00 |     20 |
	| SMITH  | CLERK     |  800.00 |     20 |

	| BLAKE  | MANAGER   | 2850.00 |     30 |
	| MARTIN | SALESMAN  | 1250.00 |     30 |
	| ALLEN  | SALESMAN  | 1600.00 |     30 |
	| TURNER | SALESMAN  | 1500.00 |     30 |
	| WARD   | SALESMAN  | 1250.00 |     30 |
	| JAMES  | CLERK     |  950.00 |     30 |
	+--------+-----------+---------+--------+
	���ɣ������ֶ����ϳ�1���ֶο����������ֶ����Ϸ��飩
	select 
		deptno, job, max(sal)
	from
		emp
	group by
		deptno, job;//д��ǰ������Ƚ��з��飬���������ǰ��Ļ������ٽ��з���

	+--------+-----------+----------+
	| deptno | job       | max(sal) |
	+--------+-----------+----------+
	|     10 | CLERK     |  1300.00 |
	|     10 | MANAGER   |  2450.00 |
	|     10 | PRESIDENT |  5000.00 |
	|     20 | ANALYST   |  3000.00 |
	|     20 | CLERK     |  1100.00 |
	|     20 | MANAGER   |  2975.00 |
	|     30 | CLERK     |   950.00 |
	|     30 | MANAGER   |  2850.00 |
	|     30 | SALESMAN  |  1600.00 |
	+--------+-----------+----------+
	
19.6��ʹ��having���ԶԷ�����֮������ݽ�һ�����ˡ�
having���ܵ���ʹ�ã�having���ܴ���where��having����
��group by����ʹ�á�

�ҳ�ÿ���������н�ʣ�Ҫ����ʾ���н�ʴ���3000�ģ�

	��һ�����ҳ�ÿ���������н��
		���ղ��ű�ŷ��飬��ÿһ�����ֵ��
		select deptno,max(sal) from emp group by deptno;
		+--------+----------+
		| deptno | max(sal) |
		+--------+----------+
		|     10 |  5000.00 |
		|     20 |  3000.00 |
		|     30 |  2850.00 |
		+--------+----------+
	
	�ڶ�����Ҫ����ʾ���н�ʴ���3000
		select 
			deptno,max(sal) 
		from 
			emp 
		group by 
			deptno
		having
			max(sal) > 3000;

		+--------+----------+
		| deptno | max(sal) |
		+--------+----------+
		|     10 |  5000.00 |
		+--------+----------+
		
```


```markdown
		˼��һ�����⣺���ϵ�sql���ִ��Ч���ǲ��ǵͣ�
		�Ƚϵͣ�ʵ���Ͽ����������ǣ��Ƚ�����3000�Ķ��ҳ�����Ȼ���ٷ��顣//��Ϊ�����Ļ�С��3000�ľͲ���Ҫ������
		
		select 
			deptno,max(sal)
		from
			emp
		where
			sal > 3000
		group by
			deptno;
		
		+--------+----------+
		| deptno | max(sal) |
		+--------+----------+
		|     10 |  5000.00 |
		+--------+----------+

		�Ż����ԣ�
			where��having������ѡ��where��whereʵ����ɲ����ˣ���ѡ��
			having��
	
	19.7��whereû�취�ģ�������
		�ҳ�ÿ������ƽ��н�ʣ�Ҫ����ʾƽ��н�ʸ���2500�ġ�

		��һ�����ҳ�ÿ������ƽ��н��
			select deptno,avg(sal) from emp group by deptno;
			+--------+-------------+
			| deptno | avg(sal)    |
			+--------+-------------+
			|     10 | 2916.666667 |
			|     20 | 2175.000000 |
			|     30 | 1566.666667 |
			+--------+-------------+

		�ڶ�����Ҫ����ʾƽ��н�ʸ���2500��
			select 
				deptno,avg(sal) 
			from 
				emp 
			group by 
				deptno
			having
				avg(sal) > 2500;
		
		+--------+-------------+
		| deptno | avg(sal)    |
		+--------+-------------+
		|     10 | 2916.666667 |
		+--------+-------------+
```





##### ˵���ˣ�where���ܶԾۺϺ������õ����ݽ��й��ˣ���ֻ�ܷ�Ӧĳ�����ݵ�����������having������ʵ��







20�����ܽᣨ����Ĳ�ѯѧ���ˣ�
	select 
		...
	from
		...
	where
		...
	group by
		...
	having
		...
	order by
		...
	

```markdown
���Ϲؼ���ֻ�ܰ������˳���������ܵߵ���

ִ��˳��
	1. from//��
	2. where//����
	3. group by//����
	4. having//ɸѡ
	5. select//��ʾ
	6. order by//����

��ĳ�ű��в�ѯ���ݣ�
�Ⱦ���where����ɸѡ���м�ֵ�����ݡ�
����Щ�м�ֵ�����ݽ��з��顣
����֮�����ʹ��having����ɸѡ��
select��ѯ������
������������

�ҳ�ÿ����λ��ƽ��н�ʣ�Ҫ����ʾƽ��н�ʴ���1500�ģ���MANAGER��λ֮�⣬
Ҫ����ƽ��н�ʽ����š�
	select 
		job, avg(sal) as avgsal
	from
		emp
	where
		job <> 'MANAGER'
	group by
		job
	having
		avg(sal) > 1500
	order by
		avgsal desc;

	+-----------+-------------+
	| job       | avgsal      |
	+-----------+-------------+
	| PRESIDENT | 5000.000000 |
	| ANALYST   | 3000.000000 |
	+-----------+-------------+
```







## ����������ڷ����ѯ�Ĳ�������������

�����ѯ
1�������ѯ�Ƕ����ݰ���ĳ�������ֶν��з��飬��MYSQL��ʹ��GROUP BY�ؼ��ֶ����ݽ��з���

2��GROUP BY�ؼ��ֿ��Խ���ѯ�������ĳ���ֶλ����ֶν��з��顣�ֶ���ֵ��ȵ�Ϊһ��
    �ŷ���ĺ����ǣ��ڲ�ѯSQL��ָ�������������Ȼ����ݸ��е�ֵ���з��飬ֵ��ȵ�Ϊһ��

3�������ѯ�Ļ������﷨��ʽ���£�

```markdown
 GROUP BY �ֶ��� [HAVING �������ʽ]
������
1���ֶ�������ָ���ո��ֶε�ֵ���з���(�����������ݵ�������)
2��HAVING�������ʽ���������Ʒ�������ʾ�������������ʽ�Ľ��������ʾ
```

��������
1�������ݽ��з��飬һ��������ʹ�ó�����
    �ŵ���ʹ��GROUP BY�ؼ��֣�
    �ƽ�GROUP BY�ؼ�����ۺϺ���һ��ʹ��(����)

2������GROUP BY�Ӿ��ʹ�ã���Ҫע�����¼��㣺
    ��GROUP BY�Ӿ���԰���������Ŀ���У�ʹ����ԶԷ������Ƕ�ף�Ϊ���ݷ����ṩ����ϸ�µĿ���
    ��GROUP BY�Ӿ��г���ÿ���ж������Ǽ����л���Ч�ı��ʽ���������ǾۺϺ���������SELECT�����ʹ�ñ��ʽ���������GROUP BY�Ӿ���ָ����ͬ�ı��ʽ

3�������ڷ�������а�����NULLֵ����NULL����Ϊһ�������ķ��鷵�أ��������д��ڶ��NULLֵ������ЩNULLֵ���ڵ��з�Ϊһ��

GROUP BY����ʹ��
����ʹ�� GROUP BY�ؼ���ʱ����ѯ�����ֻ��ʾÿ������ĵ�һ����¼

��1���޹�������ʱ

```markdown
mysql> SELECT * FROM polls_article;
+----+-----------+----------------+-------+--------+----------------------------+
| id | title     | content        | price | author | create_time                |
+----+-----------+----------------+-------+--------+----------------------------+
|  1 | ��������  | ����մ����칬 |   132 | ��ж� | 2020-09-13 14:48:30.000000 |
|  2 | ��������1 | ����ĩ������� |   154 | �޹��� | 2020-09-13 12:48:30.962070 |
|  3 | ��¥��    | �����ѽ����԰ |   154 | ��ѩ�� | 2020-09-13 12:48:30.962070 |
|  4 | ˮ䰴�    | ������ɽ       |   140 | ʩ���� | 2020-09-13 12:48:30.962070 |
|  7 | wed       | dwd            |   123 | 44     | 2020-10-13 17:08:50.493488 |
|  8 | ds        | dwd            |   123 | 32     | 2020-10-13 17:19:18.121264 |
|  9 | ���μ�    | ����ȡ��       |   345 | NULL   | 2020-11-14 15:48:59.000000 |
+----+-----------+----------------+-------+--------+----------------------------+
7 rows in set (0.00 sec)

-- ����price�ֶζ����ݽ��з���
mysql> SELECT * FROM polls_article GROUP BY price;
+----+-----------+----------------+-------+--------+----------------------------+
| id | title     | content        | price | author | create_time                |
+----+-----------+----------------+-------+--------+----------------------------+
|  7 | wed       | dwd            |   123 | 44     | 2020-10-13 17:08:50.493488 |
|  1 | ��������  | ����մ����칬 |   132 | ��ж� | 2020-09-13 14:48:30.000000 |
|  4 | ˮ䰴�    | ������ɽ       |   140 | ʩ���� | 2020-09-13 12:48:30.962070 |
|  2 | ��������1 | ����ĩ������� |   154 | �޹��� | 2020-09-13 12:48:30.962070 |
|  9 | ���μ�    | ����ȡ��       |   345 | NULL   | 2020-11-14 15:48:59.000000 |
+----+-----------+----------------+-------+--------+----------------------------+
5 rows in set (0.00 sec)
```

ע��
1������SQL��ʾ����ѯ������������(�����С���)�����Խ������"price"�ֶ�ֵ���з���
    �ŷ��飺"price"�ֶ�ֵ��ͬ��Ϊһ��
    �������ǵ���ʹ�õ�GROUP BY�ؼ��֣����ֻ�᷵��ÿ������ĵ�һ����¼

��1_1���й�������ʱ

```markdown
mysql> SELECT id,title,price,author FROM polls_article WHERE price > 130;
+----+----------+-------+--------+
| id | title    | price | author |
+----+----------+-------+--------+
|  1 | �������� |   132 | ��ж� |
|  2 | �������� |   154 | �޹��� |
|  3 | ˮ䰴�   |   154 | ��ѩ�� |
|  4 | ˮ䰴�   |   140 | ʩ���� |
|  9 | ���μ�   |   345 | NULL   |
+----+----------+-------+--------+
5 rows in set (0.00 sec)

mysql> SELECT id,title,price,author FROM polls_article WHERE price > 130 GROUP BY title;
+----+----------+-------+--------+
| id | title    | price | author |
+----+----------+-------+--------+
|  1 | �������� |   132 | ��ж� |
|  3 | ˮ䰴�   |   154 | ��ѩ�� |
|  9 | ���μ�   |   345 | NULL   |
+----+----------+-------+--------+
3 rows in set (0.00 sec)
```

ע��
1����������е�SQL��ʾ����ѯ����"price > 130"������(��ѯ�Ĳ�����)���ڶԷ�����������������"title"�ֶ�ֵ���з���
    �����ҵ����Ϲ������������ݣ�Ȼ���ٷ���

2��ǰ�����������У�����ʹ��GROUP BY�ؼ���ֻ��ʾÿ�������һ����¼
    ����˵����GROUP BY�ؼ��ֵ���ʹ��ʱ��ֻ�ܲ�ѯ��ÿ�������һ����¼
    �������������岻����ˣ�һ����ʹ�ü��Ϻ���ʱ��ʹ��GROUP BY�ؼ���

GROUP BY��ۺϺ���
1��GROUP BY�ؼ���ͨ���뼯�Ϻ���һ��ʹ�á����Ϻ�������COUNT()������SUM()������AVG()������MAX()������MIN()����

2�����GROUP BY����ۺϺ���һ��ʹ�ã���ô��ѯ��������ֶ�ȡֵ�ķ������
    ���ֶ���ȡֵ��ͬ�ļ�¼Ϊһ�飬����ֻ��ʾ����ĵ�һ����¼(��ǰ��GROUP BY����ʹ��һ��)

3�����õľۺϺ����У�
    ��COUNT()����������ͳ�Ƽ�¼������
    ��SUM()���������ڼ����ֶε�ֵ���ܺ�
    ��AVG()���������ڼ����ֶε�ֵ��ƽ��ֵ
    ��MAX()���������ڲ�ѯ�ֶε����ֵ
    ��MIN()���������ڲ�ѯ�ֶε���Сֵ

��2��

```
mysql> SELECT * FROM polls_article;
+----+----------+----------------+-------+--------+----------------------------+
| id | title    | content        | price | author | create_time                |
+----+----------+----------------+-------+--------+----------------------------+
|  1 | �������� | ����մ����칬 |   123 | ��ж� | 2020-09-13 14:48:30.000000 |
|  2 | �������� | ����ĩ������� |   154 | �޹��� | 2020-09-13 12:48:30.962070 |
|  3 | ˮ䰴�   | �����ѽ����԰ |   154 | ��ѩ�� | 2020-09-13 12:48:30.962070 |
|  4 | ˮ䰴�   | ������ɽ       |   140 | ʩ���� | 2020-09-13 12:48:30.962070 |
|  7 | wed      | dwd            |   123 | 44     | 2020-10-13 17:08:50.493488 |
|  8 | ds       | dwd            |   123 | 32     | 2020-10-13 17:19:18.121264 |
|  9 | ���μ�   | ����ȡ��       |   345 | NULL   | 2020-11-14 15:48:59.000000 |
+----+----------+----------------+-------+--------+----------------------------+
7 rows in set (0.00 sec)

-- ��ѯ�۸���ͬ��ͼ������
mysql> SELECT price, COUNT(*) FROM polls_article GROUP BY price;
+-------+----------+
| price | COUNT(*) |
+-------+----------+
|   123 |        3 |
|   140 |        1 |
|   154 |        2 |
|   345 |        1 |
+-------+----------+
4 rows in set (0.00 sec)


```

ע��
1���������ӱ�ʾ����ѯ�������е����ݣ�����"price"�ֶ�ֵ���з��飬Ȼ�����ÿ��ļ�¼����

2���ڴ�������ʱ��Ҫע�⣬һ����˵��
    �ų��ۺϺ���֮�⣬SELECT����е�ÿ���ж�������GROUP BY�Ӿ��и���

GROUP BY��GROUP_CONCAT
GROUP BY�ؼ��ֿ��Ժ�GROUP_CONCAT()����һ��ʹ�á�GROUP_CONCAT()�������ÿ��������ֶ�ֵ����ʾ����

��3��
��������������������������������

```
mysql> SELECT title,price, COUNT(*) FROM polls_article GROUP BY price;
+----------+-------+----------+
| title    | price | COUNT(*) |
+----------+-------+----------+
| �������� |   123 |        3 |
| ˮ䰴�   |   140 |        1 |
| �������� |   154 |        2 |
| ���μ�   |   345 |        1 |
+----------+-------+----------+
4 rows in set (0.00 sec)

mysql> SELECT price,COUNT(*), GROUP_CONCAT(title) AS article_title FROM polls_article GROUP BY price;
+-------+----------+-----------------+
| price | COUNT(*) | article_title   |
+-------+----------+-----------------+
|   123 |        3 | ��������,wed,ds |
|   140 |        1 | ˮ䰴�          |
|   154 |        2 | ��������,ˮ䰴� |
|   345 |        1 | ���μ�          |
+-------+----------+-----------------+
4 rows in set (0.00 sec)
```

ע�����Կ���
1�����ݷ�������ֱ�Ӳ�ѯĳ����ʱ��ֻ�᷵�ظ÷����ڵ�һ��ֵ(�����е�title��)

2����ʹ��GROUP_CONCAT()�������ͻ᷵�ظ÷��������е�ֵ

���ֶη���
1��ʹ��GROUP BY���ԶԶ���ֶν��з��飬GROUP BY�ؼ��ֺ������Ҫ������ֶ�
2��MYSQL���ݶ��ֶε�ֵ�����в�η��飬�����δ�����
    �ż��Ȱ���һ���ֶη��飬Ȼ���ڵ�һ���ֶ�ֵ��ͬ�ļ�¼�У��ٸ��ݵڶ����ֶε�ֵ���з���...һ������
    
��4��

```
mysql> SELECT * FROM polls_article;
+----+----------+----------------+-------+--------+----------------------------+
| id | title    | content        | price | author | create_time                |
+----+----------+----------------+-------+--------+----------------------------+
|  1 | �������� | ����մ����칬 |   123 | ��ж� | 2020-09-13 14:48:30.000000 |
|  2 | �������� | ����ĩ������� |   154 | �޹��� | 2020-09-13 12:48:30.962070 |
|  3 | ˮ䰴�   | �����ѽ����԰ |   154 | ��ѩ�� | 2020-09-13 12:48:30.962070 |
|  4 | ˮ䰴�   | ������ɽ       |   140 | ʩ���� | 2020-09-13 12:48:30.962070 |
|  7 | ds       | dwd            |   123 | 44     | 2020-10-13 17:08:50.493488 |
|  8 | ds       | dwd            |   123 | 32     | 2020-10-13 17:19:18.121264 |
|  9 | ���μ�   | ����ȡ��       |   345 | NULL   | 2020-11-14 15:48:59.000000 |
+----+----------+----------------+-------+--------+----------------------------+
7 rows in set (0.00 sec)

mysql> SELECT * FROM polls_article GROUP BY price,title;
+----+----------+----------------+-------+--------+----------------------------+
| id | title    | content        | price | author | create_time                |
+----+----------+----------------+-------+--------+----------------------------+
|  7 | ds       | dwd            |   123 | 44     | 2020-10-13 17:08:50.493488 |
|  1 | �������� | ����մ����칬 |   123 | ��ж� | 2020-09-13 14:48:30.000000 |
|  4 | ˮ䰴�   | ������ɽ       |   140 | ʩ���� | 2020-09-13 12:48:30.962070 |
|  2 | �������� | ����ĩ������� |   154 | �޹��� | 2020-09-13 12:48:30.962070 |
|  3 | ˮ䰴�   | �����ѽ����԰ |   154 | ��ѩ�� | 2020-09-13 12:48:30.962070 |
|  9 | ���μ�   | ����ȡ��       |   345 | NULL   | 2020-11-14 15:48:59.000000 |
+----+----------+----------------+-------+--------+----------------------------+
6 rows in set (0.00 sec)

mysql> SELECT price,COUNT(*), GROUP_CONCAT(title)  FROM polls_article GROUP BY price,title;
+-------+----------+---------------------+
| price | COUNT(*) | GROUP_CONCAT(title) |
+-------+----------+---------------------+
|   123 |        2 | ds,ds               |
|   123 |        1 | ��������            |
|   140 |        1 | ˮ䰴�              |
|   154 |        1 | ��������            |
|   154 |        1 | ˮ䰴�              |
|   345 |        1 | ���μ�              |
+-------+----------+---------------------+
6 rows in set (0.00 sec)
```

ע������������
1����ʾ���Ȱ���"price"�ֶη��飬�ٰ�"title"�ֶη���
    �ű��磺����"price"�ֶη���ʱ�����������ݣ�ds��ds�����μ�
    �ƴ�ʱ��������ڴ�����ֵͬ������
    �����������������ݼ�������"title"�ֶη���

ʹ��HAVING���˷���
1��GROUP BY���Ժ�HAVINGһ���޶���ʾ��¼���������������ֻ�����������ķ���Żᱻ��ʾ

2��HAVING�ؼ����ǶԷ��������й��ˡ�WHERE�ؼ����ǶԱ����ݽ��й���
    ������ͬʱ����ʱ���϶����ȼ���WHERE��WHERE�ų��ļ�¼�϶��ǲ�������ڷ����ڵ�

��5��

```
mysql> SELECT price,COUNT(*), GROUP_CONCAT(title) AS article_title FROM polls_article GROUP BY price;
+-------+----------+-----------------+
| price | COUNT(*) | article_title   |
+-------+----------+-----------------+
|   123 |        3 | ��������,ds,ds  |
|   140 |        1 | ˮ䰴�          |
|   154 |        2 | ��������,ˮ䰴� |
|   345 |        1 | ���μ�          |
+-------+----------+-----------------+
4 rows in set (0.00 sec)

-- ���ݰ���price���飬���ط�����ÿ��������м�����������������ڵ���2��������
mysql> SELECT price,COUNT(*), GROUP_CONCAT(title) AS article_title FROM polls_article GROUP BY price HAVING COUNT(title) >=2;
+-------+----------+-----------------+
| price | COUNT(*) | article_title   |
+-------+----------+-----------------+
|   123 |        3 | ��������,ds,ds  |
|   154 |        2 | ��������,ˮ䰴� |
+-------+----------+-----------------+
2 rows in set (0.00 sec)
```

**��5_1��**

```
mysql> SELECT price,COUNT(*), GROUP_CONCAT(title) AS article_title FROM polls_article WHERE price >130 GROUP BY price;
+-------+----------+-----------------+
| price | COUNT(*) | article_title   |
+-------+----------+-----------------+
|   140 |        1 | ˮ䰴�          |
|   154 |        2 | ��������,ˮ䰴� |
|   345 |        1 | ���μ�          |
+-------+----------+-----------------+
3 rows in set (0.00 sec)

mysql> SELECT price,COUNT(*), GROUP_CONCAT(title) AS article_title FROM polls_article WHERE price >130 GROUP BY price HAVING COUNT(title) >=2;
+-------+----------+-----------------+
| price | COUNT(*) | article_title   |
+-------+----------+-----------------+
|   154 |        2 | ��������,ˮ䰴� |
+-------+----------+-----------------+
1 row in set (0.00 sec)
```

ע��
����SQL��ʾ����ѯ����"price >130"������(WHERE)->����"price"����->���������ݸ������ڵ���2����(HAVING)

GROUP BY��WITH ROLLUP
WITH POLLUP�ؼ������������м�¼��������һ����¼��������¼���������м�¼���ܺͣ���ͳ�Ƽ�¼����

��6��
��������������������������������

```
mysql> SELECT price,COUNT(*), GROUP_CONCAT(title) AS article_title FROM polls_article GROUP BY price;
+-------+----------+-----------------+
| price | COUNT(*) | article_title   |
+-------+----------+-----------------+
|   123 |        3 | ��������,ds,ds  |
|   140 |        1 | ˮ䰴�          |
|   154 |        2 | ��������,ˮ䰴� |
|   345 |        1 | ���μ�          |
+-------+----------+-----------------+
4 rows in set (0.00 sec)

mysql> SELECT price,COUNT(*), GROUP_CONCAT(title) AS article_title FROM polls_article GROUP BY price WITH ROLLUP;
+-------+----------+----------------------------------------------+
| price | COUNT(*) | article_title                                |
+-------+----------+----------------------------------------------+
|   123 |        3 | ��������,ds,ds                               |
|   140 |        1 | ˮ䰴�                                       |
|   154 |        2 | ��������,ˮ䰴�                              |
|   345 |        1 | ���μ�                                       |
|  NULL |        7 | ��������,ds,ds,ˮ䰴�,��������,ˮ䰴�,���μ� |
+-------+----------+----------------------------------------------+
5 rows in set (0.00 sec)
```

ע��
ͨ��GROUP BY����֮������ʾ�����������������һ�У�����ÿ�е�ֵ��������������ֵ֮��

GROUP BY��ORDER BY
1��ĳЩ�������Ҫ�Է����������
    ��һ�������ORDER BY�������Բ�ѯ�����������ġ�������GROUP BYһ��ʹ��ʱ�����ԶԷ�������������

2����Ҫע�⣺��ʹ��ROLLUPʱ���Ͳ���ͬʱʹ��ORDER BY�Ӿ���н��������
    �ż���ROLLUP��ORDER BY�ǻ����ų��

��7��

```
mysql> SELECT price,COUNT(*), GROUP_CONCAT(title) AS article_title FROM polls_article GROUP BY price;
+-------+----------+-----------------+
| price | COUNT(*) | article_title   |
+-------+----------+-----------------+
|   123 |        3 | ��������,ds,ds  |
|   140 |        1 | ˮ䰴�          |
|   154 |        2 | ��������,ˮ䰴� |
|   345 |        1 | ���μ�          |
+-------+----------+-----------------+
4 rows in set (0.00 sec)

mysql> SELECT price,COUNT(*), GROUP_CONCAT(title) AS article_title FROM polls_article GROUP BY price ORDER BY article_title;
+-------+----------+-----------------+
| price | COUNT(*) | article_title   |
+-------+----------+-----------------+
|   123 |        3 | ��������,ds,ds  |
|   154 |        2 | ��������,ˮ䰴� |
|   140 |        1 | ˮ䰴�          |
|   345 |        1 | ���μ�          |
+-------+----------+-----------------+
4 rows in set (0.00 sec)
```

**��7_1��**

```
mysql> SELECT price,COUNT(*), GROUP_CONCAT(title) AS article_title FROM polls_article GROUP BY price HAVING COUNT(article_title) >= 1;
+-------+----------+-----------------+
| price | COUNT(*) | article_title   |
+-------+----------+-----------------+
|   123 |        3 | ��������,ds,ds  |
|   140 |        1 | ˮ䰴�          |
|   154 |        2 | ��������,ˮ䰴� |
|   345 |        1 | ���μ�          |
+-------+----------+-----------------+
4 rows in set (0.00 sec)

mysql>  SELECT price,COUNT(*), GROUP_CONCAT(title) AS article_title FROM polls_article GROUP BY price HAVING COUNT(article_title) >= 1 ORDER BY article_title;
+-------+----------+-----------------+
| price | COUNT(*) | article_title   |
+-------+----------+-----------------+
|   123 |        3 | ��������,ds,ds  |
|   154 |        2 | ��������,ˮ䰴� |
|   140 |        1 | ˮ䰴�          |
|   345 |        1 | ���μ�          |
+-------+----------+-----------------+
4 rows in set (0.00 sec)
```

MySQL��Oracleʹ��GROUP BY������
1��Oracle��ʹ��group byʱ����ѯ�ֶα����Ƿ�������ݻ�ۺϺ���
    ��select�Ӿ�����һ�ǾۺϺ����ֶζ�Ӧ��Դ��group by�������󣬷����﷨����벻ͨ��
    ��Ҳ����˵SELECT�Ӿ������в�ѯ��(���ۺϺ�����)����Ӧ����GROUP BY�Ӿ�����һ��

2��MySQLû�д����ƣ����Զ�ȡ��һ��
    ��SELECT�Ӿ������в�ѯ��(���ۺϺ�����)��������GROUP BY�Ӿ����в�һ��
    ��ע����ȻMysql�������ƣ�������дSQLʱ��û��Ǳ�֤SELECT�Ӿ������в�ѯ��(���ۺϺ�����)������GROUP BY�Ӿ�����һ��

��8��Mysql

```
mysql> SELECT * FROM FRUITS; --��ѯ��������
+------+--------+---------+
| f_id | f_name | f_price |
+------+--------+---------+
|    1 | apple  | 134     |
|    2 | origen | 333     |
|    3 | caomei | 134     |
|    4 | li     | 334     |
+------+--------+---------+
4 rows in set (0.00 sec)

mysql> SELECT * FROM FRUITS GROUP BY f_price; --��ѯ�����У���ѯ����GROUP BY�Ӿ�������һ��
--f_price=134��������������mysql�����з�������¾�ֻ�᷵�ص�һ�����ݣ�mysqlֻ�����⴦���
--oracle��û�����⴦�����������f_price=134�����������ݣ����ǲ�ѯ������f_name�������������ݵ�ֵ��һ�£����޷����飬��ʱ���ݿ��û��֪���÷�����������
--������oracle�в�ѯ�б������������һ�£����������������oracle�оͱ����ٰ���f_name���з���
+------+--------+---------+
| f_id | f_name | f_price |
+------+--------+---------+
|    1 | apple  | 134     |
|    2 | origen | 333     |
|    4 | li     | 334     |
+------+--------+---------+
3 rows in set (0.00 sec)

mysql> SELECT f_name FROM FRUITS GROUP BY f_price;  --��ѯָ���У���ѯ����GROUP BY�Ӿ�������һ��
+--------+
| f_name |
+--------+
| apple  |
| origen |
| li     |
+--------+
3 rows in set (0.00 sec)

mysql> SELECT f_name,COUNT(f_price) FROM FRUITS GROUP BY f_price;
+--------+----------------+
| f_name | COUNT(f_price) |
+--------+----------------+
| apple  |              2 |
| origen |              1 |
| li     |              1 |
+--------+----------------+
3 rows in set (0.00 sec)

mysql> SELECT f_name,f_price FROM FRUITS GROUP BY f_price,f_name;
+--------+---------+
| f_name | f_price |
+--------+---------+
| apple  | 134     |
| caomei | 134     |
| origen | 333     |
| li     | 334     |
+--------+---------+
4 rows in set (0.00 sec)
```

**��8_1��Oracle**

```
SQL> SELECT * FROM FRUITS;  --��ѯ��������

      F_ID F_NAME               F_PRICES

---------- -------------------- --------------------

         3 apple                345
         4 origin               123
         5 APPLE                343
         6 CAOMEI               123

SQL> SELECT * FROM FRUITS GROUP BY f_prices;  --��ѯ�����У���ѯ����GROUP BY�Ӿ�������һ��
SELECT * FROM FRUITS GROUP BY f_prices
       *
�� 1 �г��ִ���:
ORA-00979: ���� GROUP BY ���ʽ


SQL> SELECT f_name FROM FRUITS GROUP BY f_prices;  --��ѯָ���У���ѯ����GROUP BY�Ӿ�������һ��
SELECT f_name FROM FRUITS GROUP BY f_prices
       *
�� 1 �г��ִ���:
ORA-00979: ���� GROUP BY ���ʽ


SQL> SELECT f_name,count(*) FROM FRUITS GROUP BY f_prices;  --��ѯָ���У���ѯ����GROUP BY�Ӿ�������һ��
SELECT f_name,count(*) FROM FRUITS GROUP BY f_prices
       *
�� 1 �г��ִ���:
ORA-00979: ���� GROUP BY ���ʽ


SQL> SELECT f_name,f_prices,count(*) FROM FRUITS GROUP BY f_prices,f_name; --��ѯָ���У���ѯ����GROUP BY�Ӿ�����һ��

F_NAME               F_PRICES               COUNT(*)

-------------------- -------------------- ----------

apple                345                           1
origin               123                           1
APPLE                343                           1
CAOMEI               123                           1
```

