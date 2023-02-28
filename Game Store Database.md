# SQL
My Portfolio showcasing my skills at Data Analysis
# This is my Store Database for a game store.  It shows the game titles, prices, what console are their games for, and what kind of copy of the game they sell.

CREATE TABLE store_database (id INTEGER PRIMARY KEY, title TEXT, console INTEGER, price REAL, copy TEXT);

INSERT INTO store_database VALUES (1,"Cuphead","PS5, Switch", 59.99, "Physical, Digital");
INSERT INTO store_database VALUES (2,"Mario Kart","Switch", 35.99,"Physical");
INSERT INTO store_database VALUES (3,"Kirby: The Forgotten Land","Switch", 47.99,"Digital");
INSERT INTO store_database VALUES (4,"Pokemon Violet","Switch",59.99,"Physical, Digital");
INSERT INTO store_database VALUES (5, "Witcher 3: Wild Hunt","PS4, PS5, Switch", 14.99,"Digital");
INSERT INTO store_database VALUES (6, "Among Us","PC, PS5, Switch", 4.99,"Digital");
INSERT INTO store_database VALUES (7, "Spyro Re-ignited Trilogy","PS4, PS5, Switch", 24.99,"Physical");
INSERT INTO store_database VALUES (8, "Dragon Quest Builders 2","PS4, PS5, Switch", 64.99,"Physical, Digital");
INSERT INTO store_database VALUES (9, "Disney Dreamlight Valley","PS5, Switch", 34.99,"Physical");
INSERT INTO store_database VALUES (10, "Mario + Rabbids","Switch", 42.99,"Digital");
INSERT INTO store_database VALUES (11, "Disgaea 6","PS5, Switch", 46.99,"Physical, Digital");
INSERT INTO store_database VALUES (12, "Legend of Zelda: Breath of the Wild","Switch", 49.99,"Physical");
INSERT INTO store_database VALUES (13, "Pokemon Let's Go Pikachu","Switch", 49.99,"Physical");
INSERT INTO store_database VALUES (14, "Luigi's Mansion 3","Switch", 34.99,"Physical");
INSERT INTO store_database VALUES (15, "Dragon Quest Builders 1","PS4, PS5, Switch", 42.99,"Physical");
INSERT INTO store_database VALUES (16, "Dragon's Dogma","PS4, PS5, Switch", 14.99,"Digital");
INSERT INTO store_database VALUES (17, "Stardew Valley","PC, PS4, PS5, Switch", 12.99,"Digital");

-- Sort By Price in Ascending Order.

SELECT * FROM store_database
ORDER BY price ASC;


-- Sort By the type of Game Copy.

SELECT * FROM store_database
ORDER BY copy ASC;
