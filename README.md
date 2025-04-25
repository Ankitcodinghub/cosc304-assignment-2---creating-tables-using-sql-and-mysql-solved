# cosc304-assignment-2---creating-tables-using-sql-and-mysql-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/cosc-304-introduction-to-database-systems-assignment-2-creating-tables-using-sql-and-mysql-solved/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;128510&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COSC304 Assignment 2 - Creating tables using SQL and MySQL Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
<div class="kksr-stars">
    
<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
    
<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>
                

<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
This assignment practices SQL DDL.

Write the SQL DDL to create the following 5 tables describing cooking: Recipe, Ingredient, Author, Cook, Requires. Make sure that every table has a primary key.

An Author table where each author is identified by an integer id and has a name (up to 30 characters).

An Ingredient table where each ingredient has an id of exactly 5 characters and a name (up to 30 characters).

A Recipe table where each recipe is identified by a field called id that is an integer. Other attributes include name (string up to 40 characters), authorId (integer), and directions (string up to 255 characters). Make all foreign keys set to null on delete and no action (generate error) on update.

A Requires table that stores what ingredients are needed in a recipe. This table has a recipe id, ingredient id, and amount (floating point number). Make all foreign keys set to cascade on both update and delete.

Write the SQL DDL to perform the following modifications to the database created in Question 1.

Insert the following records into the appropriate tables.

Author

(1,’Joe Smith’) (2,’Fred Funk’)

Ingredient

(‘BUTTR’,’Butter’) (‘FLOUR’,’Flour’) (‘MILK’,’Milk’) (‘EGGS’,’Eggs’) (‘SUGAR’,’Sugar’)

Recipe

(100,’Cookies’,1,’Mix butter, flour, milk, eggs, and sugar. Then hope for the best.’) (200,’Bread’,2,’Knead flour with milk and eggs. Bake at 450F or until brown.’) Requires

You figure it out based on both recipes (choose your own amount).

Cook

1. Change the name of the ingredient with id ‘MILK’ to ‘Skim Milk’.

2. Increase the amount of all required ingredients used with recipe 100 by 2.

1. Delete all recipes written by ‘Fred Funk’. How many rows are deleted when this statement is run? (1 mark) Note: In addition to testing when the foreign key is ON CASCADE, also recommend you try the DELETE when the foreign key on Recipe is either SET NULL or NO ACTION to see the difference.

2. Delete all ingredients required for recipe 200 with an amount greater than 2.

Submission
