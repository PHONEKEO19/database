select * from sales.stores

select * from sales.staffs

select * from sales.orders

insert into sales.stores values ('Soutsaka store','021 77443338','keochanthanthavanh@gmail.com','Phonepanao','saysettha','VT','001')
insert into sales.stores values ('Big Brother Store','021 77443338','keochanthanthavanh@gmail.com','Sokkham','saysettha','VT','002')

insert into sales.staffs values ('chan','CTV','keochanthanthavanh@gmail.com','0207721166','1','001','001')

SELECT * from production.products
SELECT * FROM production.brands
SELECT * FROM production.categories

INSERT into production.categories VALUES ('Machine')
INSERT into production.categories VALUES ('kong')
INSERT into production.categories VALUES ('faita')

INSERT into production.products VALUES ('yamaha machine', 1,1,2022,5200000.00)
INSERT into production.products VALUES ('honeda front light', 2,3,2021,500000.00)
INSERT into production.products VALUES ('suzuki yanglor nar', 3,2,2020,500000.00)

SELECT * from production.products
SELECT production.products.product_id 'ລຳດັບ',production.products.product_name 'ຊື່ສິນຄ້າ', production.brands.brand_name 'ຊື່ຫຍີ່ຫໍ້',
production.categories.category_name 'ໝວດສີນຄ້າ', production.products.model_year 'ປີຜະລິດ', production.products.list_price 'ລາຄາ'
FROM production.products, production.brands, production.categories
WHERE production.products.product_id = production.brands.brand_id and production.products.product_id = production.categories.category_id
