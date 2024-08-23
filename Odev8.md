`SORU 1: test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.`
```SQL
CREATE TABLE employee(
	id SERIAL PRIMARY KEY,
	name VARCHAR(50) NOT NULL,
	birthday DATE,
	email VARCHAR(100)
);
```

`SORU 2: Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.`
```SQL
insert into employee (id, name, birthday, email) values (1, 'Maddi Danihel', '2024-01-26', 'mdanihel0@cam.ac.uk');
insert into employee (id, name, birthday, email) values (2, 'Antin Columbell', '2024-02-16', 'acolumbell1@amazon.de');
insert into employee (id, name, birthday, email) values (3, 'Allys Gockeler', '2024-07-08', 'agockeler2@dyndns.org');
insert into employee (id, name, birthday, email) values (4, 'Flinn Couvert', '2023-09-26', 'fcouvert3@kickstarter.com');
insert into employee (id, name, birthday, email) values (5, 'Theodoric Willman', '2023-11-20', 'twillman4@blogtalkradio.com');
insert into employee (id, name, birthday, email) values (6, 'Faith Mettetal', '2023-08-31', 'fmettetal5@quantcast.com');
insert into employee (id, name, birthday, email) values (7, 'Bartholomew Dundendale', '2024-01-27', 'bdundendale6@weebly.com');
insert into employee (id, name, birthday, email) values (8, 'Amy Armiger', '2024-06-13', 'aarmiger7@e-recht24.de');
insert into employee (id, name, birthday, email) values (9, 'Rafa Reiach', '2023-12-30', 'rreiach8@smugmug.com');
insert into employee (id, name, birthday, email) values (10, 'Weston Livett', '2024-04-07', 'wlivett9@prnewswire.com');
insert into employee (id, name, birthday, email) values (11, 'Suzann Shorie', '2024-06-25', 'sshoriea@lycos.com');
insert into employee (id, name, birthday, email) values (12, 'Ancell Leas', '2024-02-03', null);
insert into employee (id, name, birthday, email) values (13, 'Vernor Drew-Clifton', '2024-06-06', 'vdrewcliftonc@drupal.org');
insert into employee (id, name, birthday, email) values (14, 'Nanine Fulun', '2024-06-21', 'nfulund@samsung.com');
insert into employee (id, name, birthday, email) values (15, 'Steffen Athy', '2024-04-07', 'sathye@creativecommons.org');
insert into employee (id, name, birthday, email) values (16, 'Irvine McKelvey', '2024-05-14', 'imckelveyf@nasa.gov');
insert into employee (id, name, birthday, email) values (17, 'Natividad Cradock', '2023-11-05', 'ncradockg@booking.com');
insert into employee (id, name, birthday, email) values (18, 'Falkner Acland', '2024-01-01', null);
insert into employee (id, name, birthday, email) values (19, 'Paxon Haskey', null, 'phaskeyi@apple.com');
insert into employee (id, name, birthday, email) values (20, 'Mattie Ickovici', '2024-07-11', 'mickovicij@yellowpages.com');
insert into employee (id, name, birthday, email) values (21, 'Cary Pattle', '2024-06-28', 'cpattlek@histats.com');
insert into employee (id, name, birthday, email) values (22, 'Celisse Curnokk', '2024-01-07', 'ccurnokkl@diigo.com');
insert into employee (id, name, birthday, email) values (23, 'Glenna Francisco', '2024-05-20', 'gfranciscom@smugmug.com');
insert into employee (id, name, birthday, email) values (24, 'Marjory Nickless', null, 'mnicklessn@java.com');
insert into employee (id, name, birthday, email) values (25, 'Harley Aulton', null, 'haultono@nifty.com');
insert into employee (id, name, birthday, email) values (26, 'Carita Burth', '2023-10-15', 'cburthp@who.int');
insert into employee (id, name, birthday, email) values (27, 'Rodge Duckerin', '2024-03-28', 'rduckerinq@patch.com');
insert into employee (id, name, birthday, email) values (28, 'Wandis Digle', null, null);
insert into employee (id, name, birthday, email) values (29, 'Ellwood Queyos', null, 'equeyoss@networkadvertising.org');
insert into employee (id, name, birthday, email) values (30, 'Dominique Order', '2023-12-06', 'dordert@google.it');
insert into employee (id, name, birthday, email) values (31, 'Clarabelle Sidgwick', '2023-12-09', 'csidgwicku@netscape.com');
insert into employee (id, name, birthday, email) values (32, 'Isidro Hurler', '2023-10-28', null);
insert into employee (id, name, birthday, email) values (33, 'Shirline Witchard', '2024-04-22', 'switchardw@google.ca');
insert into employee (id, name, birthday, email) values (34, 'Reuben Wingfield', '2024-05-26', null);
insert into employee (id, name, birthday, email) values (35, 'Cathy Mulder', '2023-12-21', 'cmuldery@e-recht24.de');
insert into employee (id, name, birthday, email) values (36, 'Janifer Smyley', null, null);
insert into employee (id, name, birthday, email) values (37, 'Christin Aylwin', '2023-12-16', 'caylwin10@domainmarket.com');
insert into employee (id, name, birthday, email) values (38, 'Haleigh Cockling', null, 'hcockling11@blog.com');
insert into employee (id, name, birthday, email) values (39, 'Eula Westall', '2023-11-28', 'ewestall12@jalbum.net');
insert into employee (id, name, birthday, email) values (40, 'Glynn Downes', null, null);
insert into employee (id, name, birthday, email) values (41, 'Margie O'' Borne', '2024-05-30', 'mo14@ameblo.jp');
insert into employee (id, name, birthday, email) values (42, 'Salomo Reed', '2024-01-23', 'sreed15@about.com');
insert into employee (id, name, birthday, email) values (43, 'Oswald Deporte', '2024-05-25', 'odeporte16@tmall.com');
insert into employee (id, name, birthday, email) values (44, 'Marleah Halsall', '2024-03-23', 'mhalsall17@i2i.jp');
insert into employee (id, name, birthday, email) values (45, 'Sly North', '2024-03-22', null);
insert into employee (id, name, birthday, email) values (46, 'Agnola Rheam', '2024-04-26', null);
insert into employee (id, name, birthday, email) values (47, 'Ambur Sowrey', '2023-12-25', 'asowrey1a@census.gov');
insert into employee (id, name, birthday, email) values (48, 'Damita Tidbald', '2023-09-04', 'dtidbald1b@gravatar.com');
insert into employee (id, name, birthday, email) values (49, 'Lucian Tomadoni', '2023-12-17', 'ltomadoni1c@illinois.edu');
insert into employee (id, name, birthday, email) values (50, 'Engelbert Banaszkiewicz', '2024-06-23', 'ebanaszkiewicz1d@statcounter.com');
```

`SORU 3: Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.`
```SQL
UPDATE employee
SET name = 'Updated Person'
WHERE id = 1;

UPDATE employee
SET name = 'Updated Person'
WHERE id = 2;

UPDATE employee
SET name = 'Updated Person'
WHERE id = 3;

UPDATE employee
SET name = 'Updated Person'
WHERE id = 4;

UPDATE employee
SET name = 'Updated Person'
WHERE id = 5;
```

`SORU 4: Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.`
```SQL
DELETE FROM employee
WHERE id = 1;

DELETE FROM employee
WHERE id = 2;

DELETE FROM employee
WHERE id = 3;

DELETE FROM employee
WHERE id = 4;

DELETE FROM employee
WHERE id = 5;

```
