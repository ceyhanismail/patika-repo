# [Patika.dev](https://www.patika.dev) SQL

## Task 8

1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

```sql
CREATE TABLE employee (
    id INT,
    name VARCHAR(50),
    birthday DATE,
    email VARCHAR(100)    
);
```

2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

```sql
insert into employee (id, name, email, birthday ) values (1, 'Malchy Rusbridge', 'mrusbridge0@printfriendly.com', '1993-01-04');
insert into employee (id, name, email, birthday ) values (2, 'Mabelle De Vaan', 'mde1@fastcompany.com', '1913-04-16');
insert into employee (id, name, email, birthday ) values (3, 'Fiorenze Rawsthorn', 'frawsthorn2@globo.com', '1963-06-26');
insert into employee (id, name, email, birthday ) values (4, 'Timotheus Weeden', 'tweeden3@statcounter.com', '2001-10-31');
insert into employee (id, name, email, birthday ) values (5, 'Stacey Denkel', 'sdenkel4@deliciousdays.com', '1941-02-28');
insert into employee (id, name, email, birthday ) values (6, 'Fitzgerald Hannond', 'fhannond5@hostgator.com', '2012-12-21');
insert into employee (id, name, email, birthday ) values (7, 'Judas Lebreton', 'jlebreton6@census.gov', '1904-09-04');
insert into employee (id, name, email, birthday ) values (8, 'Aimee Widdall', 'awiddall7@opera.com', '1967-11-09');
insert into employee (id, name, email, birthday ) values (9, 'Allyn Regler', 'aregler8@reverbnation.com', '1955-09-02');
insert into employee (id, name, email, birthday ) values (10, 'Ezmeralda Laurenty', 'elaurenty9@irs.gov', '1988-10-29');
insert into employee (id, name, email, birthday ) values (11, 'Olav Syddie', 'osyddiea@google.com.br', null);
insert into employee (id, name, email, birthday ) values (12, 'Jolene Scrogges', 'jscroggesb@theglobeandmail.com', '1972-11-13');
insert into employee (id, name, email, birthday ) values (13, 'Tait Acaster', 'tacasterc@ask.com', '1983-07-27');
insert into employee (id, name, email, birthday ) values (14, 'Seth Galbreth', 'sgalbrethd@flavors.me', '1939-08-27');
insert into employee (id, name, email, birthday ) values (15, 'Donni Passion', 'dpassione@imageshack.us', '1990-09-10');
insert into employee (id, name, email, birthday ) values (16, 'Merrick Gonnard', 'mgonnardf@addtoany.com', '1916-01-10');
insert into employee (id, name, email, birthday ) values (17, 'Quent Giral', null, '1937-08-22');
insert into employee (id, name, email, birthday ) values (18, 'Bamby Wyard', 'bwyardh@photobucket.com', '1914-07-03');
insert into employee (id, name, email, birthday ) values (19, 'Reider Georgi', null, '1989-01-05');
insert into employee (id, name, email, birthday ) values (20, 'Braden Le Blond', 'blej@bandcamp.com', null);
insert into employee (id, name, email, birthday ) values (21, 'Octavia Burniston', 'oburnistonk@quantcast.com', '1995-03-04');
insert into employee (id, name, email, birthday ) values (22, 'Pamella Asbery', 'pasberyl@businessweek.com', '1955-01-09');
insert into employee (id, name, email, birthday ) values (23, 'Herta Mathews', null, '2016-03-14');
insert into employee (id, name, email, birthday ) values (24, 'Frederik Fears', 'ffearsn@naver.com', '2015-09-02');
insert into employee (id, name, email, birthday ) values (25, 'Lorne Dacke', 'ldackeo@shop-pro.jp', null);
insert into employee (id, name, email, birthday ) values (26, 'Novelia Larroway', 'nlarrowayp@taobao.com', '1928-07-21');
insert into employee (id, name, email, birthday ) values (27, 'Diandra Domenichelli', null, '1909-09-06');
insert into employee (id, name, email, birthday ) values (28, 'Orel Pattison', 'opattisonr@bluehost.com', '1987-01-31');
insert into employee (id, name, email, birthday ) values (29, 'Orv Cosslett', 'ocossletts@psu.edu', '1918-04-12');
insert into employee (id, name, email, birthday ) values (30, 'Arleta Banfill', null, '1979-05-18');
insert into employee (id, name, email, birthday ) values (31, 'Giorgi Olczak', 'golczaku@dailymail.co.uk', '1956-10-07');
insert into employee (id, name, email, birthday ) values (32, 'Syman Rimer', 'srimerv@mysql.com', '1965-05-06');
insert into employee (id, name, email, birthday ) values (33, 'Ashleigh Sansom', 'asansomw@amazon.de', '1995-01-18');
insert into employee (id, name, email, birthday ) values (34, 'Lira McDavitt', 'lmcdavittx@edublogs.org', '1994-06-08');
insert into employee (id, name, email, birthday ) values (35, 'Sula Malcher', 'smalchery@hexun.com', '2005-04-21');
insert into employee (id, name, email, birthday ) values (36, 'Gaylord De Mitri', 'gdez@macromedia.com', '1903-08-31');
insert into employee (id, name, email, birthday ) values (37, 'Anitra Tingey', 'atingey10@hud.gov', null);
insert into employee (id, name, email, birthday ) values (38, 'Mike Brough', 'mbrough11@exblog.jp', '1902-03-22');
insert into employee (id, name, email, birthday ) values (39, 'Ivan Boutton', 'iboutton12@unesco.org', '1998-01-07');
insert into employee (id, name, email, birthday ) values (40, 'Millisent Mibourne', 'mmibourne13@jugem.jp', '1981-09-07');
insert into employee (id, name, email, birthday ) values (41, 'Giuditta O''Flynn', 'goflynn14@blogger.com', '1955-01-27');
insert into employee (id, name, email, birthday ) values (42, 'Beverie Roscamp', 'broscamp15@goo.ne.jp', '2007-03-17');
insert into employee (id, name, email, birthday ) values (43, 'Roberto Kalb', 'rkalb16@posterous.com', null);
insert into employee (id, name, email, birthday ) values (44, 'Agatha MacAlees', 'amacalees17@illinois.edu', null);
insert into employee (id, name, email, birthday ) values (45, 'Darryl Hounson', 'dhounson18@google.ca', null);
insert into employee (id, name, email, birthday ) values (46, 'Glennie O''Shaughnessy', 'goshaughnessy19@apache.org', '2005-06-10');
insert into employee (id, name, email, birthday ) values (47, 'Gretal Stearne', 'gstearne1a@hibu.com', '2006-03-19');
insert into employee (id, name, email, birthday ) values (48, 'Amandie Dunnico', 'adunnico1b@sun.com', '1909-11-05');
insert into employee (id, name, email, birthday ) values (49, 'Frankie Medlin', 'fmedlin1c@dion.ne.jp', null);
insert into employee (id, name, email, birthday ) values (50, 'Izabel Moynihan', 'imoynihan1d@gov.uk', '2009-03-12');
```

3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

```sql
UPDATE employee
SET birthday = '1976-01-11'
WHERE name = 'Braden Le Blond'
```

```sql
UPDATE employee
SET birthday = '2001-04-03',
	email = 'namesurname@gmail.com'
WHERE name = 'Frankie Medlin';
```

```sql
UPDATE employee
SET name ='NO_NAME'
WHERE name LIKE '%l';
```

```sql
UPDATE employee
SET name ='Hello',
	birthday = '1988-07-09'
WHERE email = 'imoynihan1d@gov.uk';
```

```sql
UPDATE employee
SET name ='ADULT'
WHERE birthday > '2000-12-01';
```

4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

```sql
DELETE FROM employee
WHERE birthday = '2007-03-17';
```

```sql
DELETE FROM employee
WHERE email LIKE '@psu.edu';
```

```sql
DELETE FROM employee
WHERE name LIKE 'A%';
```

```sql
DELETE FROM employee
WHERE id >46;
```

```sql
DELETE FROM employee
WHERE birthday < '1948-03-17';
```

