# InventoryManagmentSystem(ETG Assignment)

In this IMS project there are 5 files:<br/>

1.IMS.ipynb<br/>
2.update_IMS.ipynb<br/>
3.records.json<br/>
4.sales.json<br/>
5.sales.txt<br/>

IMS.ipynb -->It has program to purhase products and display sales data.

update.ipynb --->It has program to update inventory.

records.json  -->It keep records of products

sales.json -->It keep records of sales made in json format(This is the main file for keeping track sales)

sales.txt -->It keep records of sales made record in txt format

* In this project basically there is an inventory.Customer can purchase n no. of items ( where n<no. of different items present in inventory)  by entering "product_id". After the sucessfull purchase bill is printed which has all the details of the purchase made. And if purchase is invalid it will display the necessary message.And finally "records.json","sales.json" and "sales.txt" is updated based on purcahse.(All the codes for this is on "IMS.ipynb")

* Also,we can update the inventory one at time i.e, we can add,delete,or add more quantity to the existing "product_id".(Code for this is in "update.ipynb")

The various attribute of products which is stored in "records.json" are:<br/>
i.product_id(which is used as key which maps to below details)<br/> 
ii."name" ,iii."type" ,iv."brand" ,v."mrp" ,vi."exp_date" ,vii."weight" viii. "quantity"

*product_id-->{"name","type","brand","mrp","exp_date","weight","quantity"}


The various attribute stored in "sales.json" are:<br/>
i.Refrence_id(Used as key to map below details)<br/>
ii."Customer_Name"<br/>
iii."Product_id" which maps to {"Product_id","Quantity","Cost"}(for each products purchased)><br/>
iv."Total_Amount"

*Refrence_id-->{Customer_Name, Date_Time, Product_id-->{Product_id,Quantity,Cost}(for each product purchased), Total_Amount(excluding GST)}

