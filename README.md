[отчет 3 практика.sql](https://github.com/user-attachments/files/35082616/3.sql)
[Uploading отчет 3 Косьянюк и Присяжнюк.docx…]()
INSERT INTO sellers (id, company_name, inn, rating) 
VALUES (999, 'Неизвестный продавец', '000000000000', 0.0)
ON CONFLICT (id) DO NOTHING; 
