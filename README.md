# Product Discount and Product Special by Weekday
Create a discount or special product by weekday on the Opencart

# Versions Supported and tested:
3.x: 
2.x: 2.1.0.2; 2.2.0.0
(Please, test in your version and report any problems)


# SQL for create custom field
ALTER TABLE `TABLE_PREFIX_product_special` ADD COLUMN `weekday` VARCHAR(100) NULL AFTER `date_end`; 
ALTER TABLE `TABLE_PREFIX_product_discount` ADD COLUMN `weekday` VARCHAR(100) NULL AFTER `date_end`; 
