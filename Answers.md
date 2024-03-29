<h2>1. Explain the relationship between the "Product" and "Product_Category" entities from the above diagram.</h2>
<p>Based on the schema diagram:</p>
<ul>
    <li>The <code>"Product"</code> entity has foreign key <code>"category_id"</code> that references the primary key <code>"id"</code> in the <code>"Product_Category"</code> entity.</li>
    <li>The <code>"Product"</code> and <code>"Product_Category"</code> entities has many-to-one relationship. That is, many products can belong to same category</li>
</ul>

<hr>

<h2>2. How could you ensure that each product in the "Product" table has a valid category assigned to it?</h2>
<p>
    To ensure that each product in the <code>"Product"</code> table has a valid category assigned to it, we can use foreign key constraint.In the provided schema diagram, the <code>"category_id"</code> column in the <code>"Product"</code> table is a foreign key that references the <code>"id"</code> column in the <code>"Product_Category"</code> table. This ensures the referential integrity.
    <br><br>
    The database schema provided in answer of next question.
</p>

<hr>

<h2>3. Create schema in any Database script or any ORM (Object Relational Mapping).</h2>
<p>I am using Sql commands to create database schema. The answer is in <a href="./schema.sql">schema.sql</a></p>