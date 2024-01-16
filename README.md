# Project Sporting goods store
The data presented in the case contains information about the operation of a cycling goods store (bicycles, accessories, sportswear, spare parts, etc.) and is stored in four datasets (Sales, Product, Customers, Territories).
Based on the case data, you can conduct ABC-XYZ-RFM analysis for products and customers, customer outflow Churn (Yes/No), develop a discount program, look at sales dynamics, time series analysis, search for anomalies and association rules.
 
"customers" contains data about customers:
Customer Key - customer id
FirstName - client name
Last Name - client's last name
Full Name - full name of the client
Birth Date - date of birth
Marital Status - marital status
Gender - gender
Yearly Income - annual income
Total Children - total number of children
Number ChildrenAt Home - number of children in the house
Education - client education
Occupation - client's profession
House Owner Flag - availability of real estate (house)
Number Cars Owned - number of cars owned
AddressLine1 - client’s residential address
Date First Purchase - date of first purchase
Commute Distance - travel distance
Customer City - client's city
Customer State Code - customer state (region) code
Customer State - state (region) of the client
Customer Country - client country

“products” contains data about products:
Product Key - product id
ProductName - product name
Sub Category - subcategory
Category - category
Standard Cost - standard cost
Color - color
List Price - price list
Days To Manufacture - date of manufacture
Product Line - product line
Model Name - model name
Photo - photo
Product Description - product description
StartDate - sales start date

“territories” contains data on sales regions
Sales Territory Key - seller id
Region - region
Country - country
Group - group of countries
Region Image - image of the region
Region Info - information about the region

"sales" contains sales data:
Product Key - product id
Order Date - order date
Ship Date - date of shipment
Customer Key - customer id
Promotion Key - advertising key
Sales Territory Key - seller id
Sales Order Number - registration key
Sales Order Line Number - order number
Order Quantity - order quantity
Unit Price - price for 1 unit of goods
Total Product Cost - total cost of production
Sales Amount - sales volume
Tax Amt - tax amount

Данные, представленные в кейсе, содержат в себе информацию о работе магазина товаров для велосипедного спорта (велосипеды, аксессуары, одежда для спорта, запчасти и другое) и хранятся в четырех датасетах (Sales, Product, Customers, Territories).
По данным кейса можно провести ABC-XYZ-RFM- анализ по товарам и клиентам, отток клиентов Churn(Yes/No), разработать дисконтную программу, посмотреть динамику продаж, анализ временных рядов, поиск аномалий и ассоциативных правил. 
 
«customers» содержит данные о покупателях:
Customer Key -  id  клиента
FirstName - имя клиента
Last Name - фиамилия клиента
Full Name - полные ФИО клиента
Birth Date - дата рождения 
Marital Status - семейное положение 
Gender - пол 
Yearly Income - годовой доход 
Total Children -  общее количество детей
Number ChildrenAt Home - количество детей в доме
Education - образование клиента
Occupation - профессия клиента 
House Owner Flag - наличие недвижимости (дома)
Number Cars Owned - количество машин в собственности
AddressLine1 - адрес проживания клиента
Date First Purchase - дата первой покупки
Commute Distance - расстояние в пути
Customer City - город клиента
Customer State Code - код штата (региона) клиента
Customer State - штат (регион) клиента
Customer Country - страна клиента

«products» содержит данные о товарах:
Product Key - id родукта 
ProductName - название продукта 
Sub Category - подкатегория 
Category - категория 
Standard Cost - стандартная стоимость 
Color - цвет
List Price - прайс-лист
Days To Manufacture - дата изготовления
Product Line - продуктовая линейка
Model Name - название модели
Photo - фото 
Product Description - описание продукта 
StartDate - дата начала продаж

«territories» содержит данные о регионах продаж 
Sales Territory Key - id  продавца
Region - регион 
Country - страна
Group - группа стран 
Region Image - изображение региона 
Region Info - информация о регионе

«sales» содержит данные о продажах:
Product Key - id товара
Order Date - дата заказа 
Ship Date - дата отгрузки 
Customer Key - id покупателя 
Promotion Key - рекламный ключ 
Sales Territory Key - id продавца 
Sales Order Number - регистрационный ключ 
Sales Order Line Number - номер заказа 
Order Quantity - количество заказа 
Unit Price - цена за 1 единицу товара 
Total Product Cost - общая стоимость продукции 
Sales Amount - объем продаж 
Tax Amt - сумма налогов
