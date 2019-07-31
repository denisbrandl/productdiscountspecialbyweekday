# Product Discount and Product Special by Weekday
Create a discount or special product by weekday on the Opencart

# SQL for create custom field
ALTER TABLE `TABLE_PREFIX_product_special` ADD COLUMN `weekday` VARCHAR(100) NULL AFTER `date_end`; 
ALTER TABLE `TABLE_PREFIX_product_discount` ADD COLUMN `weekday` VARCHAR(100) NULL AFTER `date_end`; 
