MR singh is responsible for setting up an inventory system in a supermarket.he creates a database table, 
INVENTORY,to store the imformation on product for sale


CREATE TABLE inventory (
    category varchar(255),
    productcode varchar(255),
    Name varchar(255),
    price int(255),
    Qty int(255)
);

QUERY TO INSERT DATA INTO RAWS

INSERT INTO inventory (category, productcode, name, price, Qty)
VALUES ('BEVERAGE', 'B163', 'BESTJUICE', 10, 10),
('SNACK','S968','YUMMY',12,40),
('NOODLE','N042','WOW',20,20),
('BEVERAGE','B482','FRESH tea',25,80),
('noodle','N091','QQ NOODLE',8,50);

QUES 1 WHICH FIELD,CAT,CODE,NAME,PRICE,OR QTY,SHOULD BE USED AS A KEY FIELD?
 
ANSWER- PRODUCT CODE IS USED AS A PRIMERY KEY

QUES2 THE DATA TYPE OF Qty is integer ,judy,mr singh colleague suggested changing into real number or string.MR singh
disagree why judy's suggestion. why?

answer2 QTY's data type should be integer only because (1) QTY can never be in fractions hence real number is not
required .
(2) QTY must be a numeric datatype not a string type as it is required in calculations.

Ques3 MR singh write the following SQl command .based on the five given record in INVENTORY above,what is the query result?

answer3 NO42  20
