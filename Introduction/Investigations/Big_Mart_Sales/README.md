# Big Mart Sales Investigation 

**This is an Analytic Investigation of the Big Mart Sales Dataset, In 2013 Big Mart Data Scientists collected sales data for 1559 different products, from 10 different st and their attributes (12 Variables). The Dataset is used to find out the sales of a particular product at a particular store.**

In this Investigation we will try to find realtionships between each item\`s attributes and it\`s sales. Exploring the data and Visualizing our findings to better understand the datasets secrets. The dataset contains 8523 records of different 1559 product and 12 attributes for each product.

#### Data Attrbutes 
- ***Item_Identifier***: It is a unique product ID assigned to every distinct item. It consists of an alphanumeric string of length 5.
- ***Item_Weight***: This field includes the wieght of the product.
- ***Item_Fat_Content***: This attribute is categorical and describes whether the product is low fat or not. There are 2 categories of this attribute: `['Low Fat', 'Regular']`. However, it is important to note that 'Low Fat' has also been written as 'low fat' and 'LF' in dataset, whereas, 'Regular' has been referred as 'reg' as well.
- ***Item_Visibility***: This field mentions the percentage of total display area of all products in a store allocated to the particular product.
- ***Item_Type***: This is a categorical attribute and describes the food category to which the item belongs. There are 16 different categories listed as follows: `['Dairy', 'Soft Drinks', 'Meat', 'Fruits and Vegetables', 'Household', 'Baking Goods', 'Snack Foods', 'Frozen Foods', 'Breakfast', 'Health and Hygiene', 'Hard Drinks', 'Canned', 'Breads', 'Starchy Foods', 'Others', 'Seafood']`. 
- ***Item_MRP***: This is the Maximum Retail Price (list price) of the product.
- ***Outlet_Identifier***: It is a unique store ID assigned. It consists of an alphanumeric string of length 6.
- ***Outlet_Establishment_Year***: This attribute mentions the year in which store was established.
- ***Outlet_Size***: The attribute tells the size of the store in terms of ground area covered. It is a categorical value and described in 3 categories: `['High', 'Medium', 'Small']`.
- ***Outlet_Location_Type***: This field has categorical data and tells about the size of the city in which the store is located through 3 categories: `['Tier 1', 'Tier 2', 'Tier 3']`.
- ***Outlet_Type***: This field contains categorical value and tells whether the outlet is just a grocery store or some sort of supermarket. Following are the 4 categories in which the data is divided: `['Supermarket Type1', 'Supermarket Type2', 'Grocery Store','Supermarket Type3']`.
- ***Item_Outlet_Sales***: This is the outcome variable to be predicted. It contains the sales of the product in the particulat store.