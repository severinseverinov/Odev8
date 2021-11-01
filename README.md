# Patika Odev 8

### Aşağıdaki sorgu senaryoları postgres SQL de gerçekleştirildi.

1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
> CREATE TABLE employee(
	id SERIAL PRIMARY KEY,
	name VARCHAR(50), 
	birthday DATE, 
	email VARCHAR(100)
);

2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
> insert into employee (name, birthday, email) values ('Marabel', '1979-04-19', 'mveare0@issuu.com');
insert into employee (name, birthday, email) values ('Monroe', '1920-10-22', 'mcastellanos1@chron.com');
insert into employee (name, birthday, email) values ('Olive', '1946-12-14', 'omcpaik2@t.co');
insert into employee (name, birthday, email) values ('Garrot', '2000-01-06', 'gmcwhinnie3@people.com.cn');
insert into employee (name, birthday, email) values ('Adorne', '1955-02-08', 'ahuman4@naver.com');
insert into employee (name, birthday, email) values ('Chickie', '1994-07-20', 'cmelsom5@instagram.com');
insert into employee (name, birthday, email) values ('Sherie', '1942-08-16', 'sgaskin6@discuz.net');
insert into employee (name, birthday, email) values ('Rodrigo', '1970-06-15', 'redelston7@oracle.com');
insert into employee (name, birthday, email) values ('Neall', '1912-06-29', 'nrumble8@wunderground.com');
insert into employee (name, birthday, email) values ('Lishe', '1938-10-19', 'lantognazzi9@google.co.uk');
insert into employee (name, birthday, email) values ('Dorthy', '1990-05-30', 'dgildroya@vistaprint.com');
insert into employee (name, birthday, email) values ('Martguerita', '1903-07-05', 'mfaltinb@google.com.au');
insert into employee (name, birthday, email) values ('Andrea', '1902-10-07', 'aeglisec@alexa.com');
insert into employee (name, birthday, email) values ('Casey', '2010-06-09', 'cphilipsohnd@toplist.cz');
insert into employee (name, birthday, email) values ('Merrile', '2001-12-20', 'mseggiee@biglobe.ne.jp');
insert into employee (name, birthday, email) values ('Caro', '2020-02-22', 'ciacovaccif@exblog.jp');
insert into employee (name, birthday, email) values ('Pattie', '2008-05-26', 'pcogglesg@un.org');
insert into employee (name, birthday, email) values ('Becky', '1907-09-25', 'bdunnionh@blogger.com');
insert into employee (name, birthday, email) values ('Giffard', '2012-04-10', 'goscolleei@nature.com');
insert into employee (name, birthday, email) values ('Ofella', '1935-10-03', 'owinsborrowj@1und1.de');
insert into employee (name, birthday, email) values ('Carolus', '1972-07-27', 'chuffeyk@example.com');
insert into employee (name, birthday, email) values ('Hettie', '1985-01-06', 'hivachyovl@npr.org');
insert into employee (name, birthday, email) values ('Katey', '1982-08-17', 'kschultzm@wired.com');
insert into employee (name, birthday, email) values ('Wenona', '1901-01-12', 'whandforthn@360.cn');
insert into employee (name, birthday, email) values ('Thacher', '1924-09-16', 'tbuckhamo@twitpic.com');
insert into employee (name, birthday, email) values ('Zonnya', '1906-07-22', 'zliklyp@instagram.com');
insert into employee (name, birthday, email) values ('Merci', '1995-01-24', 'mbillanieq@latimes.com');
insert into employee (name, birthday, email) values ('Marlin', '1910-09-14', 'mgoslinr@state.tx.us');
insert into employee (name, birthday, email) values ('Augy', '1936-04-05', 'amembrys@desdev.cn');
insert into employee (name, birthday, email) values ('Marga', '1981-11-07', 'mvanderbrugt@amazonaws.com');
insert into employee (name, birthday, email) values ('Lonnie', '1901-08-07', 'lbolusu@google.com.hk');
insert into employee (name, birthday, email) values ('Archer', '2020-02-06', 'amacknishv@1und1.de');
insert into employee (name, birthday, email) values ('Guglielmo', '2020-02-27', 'gsmidmoorw@sakura.ne.jp');
insert into employee (name, birthday, email) values ('Merla', '2017-05-31', 'mvialsx@army.mil');
insert into employee (name, birthday, email) values ('Ruddie', '2018-02-27', 'rdopplery@squarespace.com');
insert into employee (name, birthday, email) values ('Ernaline', '1917-06-16', 'ekilbanz@hibu.com');
insert into employee (name, birthday, email) values ('Sibylla', '1956-05-18', 'sflude10@icio.us');
insert into employee (name, birthday, email) values ('Hildegarde', '2007-03-23', 'hgreenlies11@cbc.ca');
insert into employee (name, birthday, email) values ('Maible', '1929-12-26', 'mruffell12@ehow.com');
insert into employee (name, birthday, email) values ('Electra', '2010-02-19', 'erecord13@discuz.net');
insert into employee (name, birthday, email) values ('Electra', '1953-03-08', 'eguerola14@cornell.edu');
insert into employee (name, birthday, email) values ('Iain', '1982-01-15', 'iwhitemarsh15@cisco.com');
insert into employee (name, birthday, email) values ('Aksel', '1913-06-16', 'agilhouley16@reverbnation.com');
insert into employee (name, birthday, email) values ('Gilburt', '1976-01-15', 'gmclachlan17@com.com');
insert into employee (name, birthday, email) values ('Aryn', '1943-07-21', 'awhorlton18@thetimes.co.uk');
insert into employee (name, birthday, email) values ('Rick', '2016-05-23', 'rcalton19@hibu.com');
insert into employee (name, birthday, email) values ('Paul', '1993-04-25', 'ppawels1a@examiner.com');
insert into employee (name, birthday, email) values ('Kori', '2000-02-12', 'kcompson1b@yahoo.com');
insert into employee (name, birthday, email) values ('Alix', '1906-12-15', 'aokker1c@ow.ly');
insert into employee (name, birthday, email) values ('Dorothee', '2003-11-16', 'dchallener1d@google.ru');

3. Sütunların her birine göre diğer sütunları güncelleyecek 4 adet UPDATE işlemi yapalım.
> UPDATE employee
SET name='Sevgin',
	birthday='1985-04-28',
	email='sevgin@serbest.com'
WHERE id=4;

> UPDATE employee
SET birthday='1988-04-28',
	email='sevginserbest@serbest.com'
WHERE name='Sevgin';

> UPDATE employee
SET name='Severin SEVERINOV',
	email='severin@serbest.com'
WHERE birthday='1988-04-28';

> UPDATE employee
SET name='Severin SEVERINOV ISAEV',
	birthday='1985-04-28'
WHERE email='severin@serbest.com';

> UPDATE employee
SET name='XXX',
    email='xxx@yyy.com',
    birthday='1980-01-01'
WHERE name LIKE 'C%';

4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
> DELETE FROM employee
WHERE id=11;

> DELETE FROM employee
WHERE name='XXX';

> DELETE FROM employee
WHERE birthday='1946-12-14';

> DELETE FROM employee
WHERE email='aeglisec@alexa.com';

> DELETE FROM employee
WHERE id>15;