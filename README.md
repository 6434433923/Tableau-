# Tableau-AdvventureWorkDW2019

this project represent in my intro to data warehouse and data mining class.

#Dashboard

![AdventureDashboard](https://github.com/6434433923/Tableau-AdvventureWorkDW2019/assets/111390371/7f0b8401-39ee-469e-88f9-f2ff052d116a)


# Total Sales
Sum of Sales Amount. The data is filtered on Sales Territory Country and Order Date Year. The Sales Territory Country filter keeps 7 of 7 members. The Order Date Year filter keeps 2010, 2011, 2012, 2013 and 2014.

<img width="241" alt="Screenshot 2566-10-23 at 23 46 55" src="https://github.com/6434433923/Tableau-AdvventureWorkDW2019/assets/111390371/e1a1e47f-8cd9-43c6-96d4-913c8b22658a">

# Sales by year
The trend of sum of Sales Amount for Order Date Month.  Color shows details about Order Date Year.  The marks are labeled by sum of Sales Amount.  Details are shown for Order Date Year. The data is filtered on Sales Territory Country, which keeps 7 of 7 members. The view is filtered on Order Date Year, which keeps 2010, 2011, 2012, 2013 and 2014.

<img width="1059" alt="Screenshot 2566-10-23 at 23 49 35" src="https://github.com/6434433923/Tableau-AdvventureWorkDW2019/assets/111390371/a24619e4-b0e7-4d90-a900-67be8f70957c">

# Sales by map (drilldown)
Region -> country -> state -> city
there are 4 graph
-Map based on Longitude (generated) and Latitude (generated).  Color shows sum of Sales Amount.  The marks are labeled by Sales Territory Group.  Details are shown for Sales Territory Group.

<img width="879" alt="Screenshot 2566-10-24 at 00 01 02" src="https://github.com/6434433923/Tableau-AdvventureWorkDW2019/assets/111390371/72084097-b452-4ee9-a82a-fcd7d5317db5">

-Map based on Longitude (generated) and Latitude (generated).  Color shows sum of Sales Amount.  The marks are labeled by Sales Territory Country.  Details are shown for Sales Territory Group and Sales Territory Country. The data is filtered on Region Filter, which keeps True.

<img width="865" alt="Screenshot 2566-10-24 at 00 01 08" src="https://github.com/6434433923/Tableau-AdvventureWorkDW2019/assets/111390371/c2c851b6-56e4-4391-990b-375f3f602566">

- Map based on Longitude (generated) and Latitude (generated).  Color shows sum of Sales Amount.  The marks are labeled by State Province Name.  Details are shown for Sales Territory Group, Sales Territory Country and State Province Name. The data is filtered on Region Filter and Country Filter. The Region Filter filter keeps True. The Country Filter filter keeps True.

 <img width="851" alt="Screenshot 2566-10-24 at 00 01 15" src="https://github.com/6434433923/Tableau-AdvventureWorkDW2019/assets/111390371/d2f23ef3-322a-4f21-a4ee-94154dae7955">

-Map based on Longitude (generated) and Latitude (generated).  Size shows sum of Sales Amount.  The marks are labeled by City.  Details are shown for various dimensions. The data is filtered on Region Filter, Country Filter and State Filter. The Region Filter filter keeps True. The Country Filter filter keeps True. The State Filter filter keeps True.

<img width="823" alt="Screenshot 2566-10-24 at 00 01 21" src="https://github.com/6434433923/Tableau-AdvventureWorkDW2019/assets/111390371/3bbbece3-61a3-47a0-9051-a55838264ab9">

# Sales per employees in 2010 - 2014
Sum of Sales Amount for each Order Date Year broken down by First Name.  Color shows details about Order Date Year. The data is filtered on Full Date Alternate Key Year, Country Region Code, State Province Name and Order Date Month. The Full Date Alternate Key Year filter has multiple members selected. The Country Region Code filter keeps multiple members. The State Province Name filter keeps multiple members. The Order Date Month filter keeps 12 of 12 members. The view is filtered on Order Date Year, which keeps 2010, 2011, 2012, 2013 and 2014.

<img width="1058" alt="Screenshot 2566-10-24 at 00 12 59" src="https://github.com/6434433923/Tableau-AdvventureWorkDW2019/assets/111390371/42cd05c6-a344-4b8b-8fd6-301e5f6bf195">

# Sales by product type
English Product Name (color) and sum of Sales Amount (size). The data is filtered on Order Date Month, Country Region Code, State Province Name and Order Date Year. The Order Date Month filter keeps 12 of 12 members. The Country Region Code filter keeps multiple members. The State Province Name filter keeps multiple members. The Order Date Year filter keeps 2010, 2011, 2012, 2013 and 2014.

<img width="167" alt="Screenshot 2566-10-24 at 00 13 53" src="https://github.com/6434433923/Tableau-AdvventureWorkDW2019/assets/111390371/dadea72b-cbb8-4d3d-a545-bd5fd9496817">

# Most order product
English Product Name.  Size shows sum of Order Quantity.  The marks are labeled by English Product Name. The data is filtered on Order Date Month, Country Region Code, State Province Name and Order Date Year. The Order Date Month filter keeps 12 of 12 members. The Country Region Code filter keeps multiple members. The State Province Name filter keeps multiple members. The Order Date Year filter keeps 2010, 2011, 2012, 2013 and 2014. The view is filtered on sum of Order Quantity, which keeps non-Null values only.


<img width="167" alt="Screenshot 2566-10-24 at 00 13 53" src="https://github.com/6434433923/Tableau-AdvventureWorkDW2019/assets/111390371/062e41f4-82f1-486a-a06a-f8d6f4dfbcd6">


# Top sales employees
Sum of Sales Amount for each First Name. The data is filtered on Order Date Month, Country Region Code, State Province Name, Order Date Year and Index. The Order Date Month filter keeps 12 of 12 members. The Country Region Code filter keeps multiple members. The State Province Name filter keeps multiple members. The Order Date Year filter keeps 2010, 2011, 2012, 2013 and 2014. The Index filter keeps 10 members.

<img width="688" alt="Screenshot 2566-10-24 at 00 15 39" src="https://github.com/6434433923/Tableau-AdvventureWorkDW2019/assets/111390371/795a27a3-2c9a-4aa3-b449-ef40deffbcb8">



