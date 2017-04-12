# Categories

Categories serve as the navigation that appear underneath the `Inventory` page, and ultimate allow the user to get to the right product quicker. 

Before adding any inventory to the system, it's important to add the corrosponding categories first, as each inventory item will need a category. Categories can be added/updated/deleted at any time. 

## Adding a Category

To add a category: 
* Navigate to {{ book.url }}/admin/inventory/categories/home.
* Click `New`

<figure>
    <img src="/assets/add-category.png" height="300" />
    <figcaption>Reset your Password Screen</figcaption>
</figure>

* Enter in the new category name first.
* The `slug` (what appears in the address bar) will be automatically generated.
* Does the category belong to another category? If so, select the parent category from the dropdown list. 
* Click `New`

## Update a Category

To update a category:
* Navigate to {{ book.url }}/admin/inventory/categories/home.
* Choose the category from the list.
* Make whatever changes are necessary to the category.
* Click `Save`

### Default Details/Features/Facets 

To save the user time, rather than apply the same details (i.e. Voltage, Length, Height, etc.) to every inventory item, we've implemented default details for categories. What this means is that any inventory that's created in a category with default details, those `details` will be applied to the inventory. 

As an example, here's a category with 3 default details:

1. Year
2. Cost
3. Voltage

When a user creates an inventory item in that category, those 3 details are automatically applied to the inventory item. The user will need to fill in the values for those details, or delete them if not necessary. 

<figure>
    <img src="/assets/default-details.jpg"/>
    <figcaption>Reset your Password Screen</figcaption>
</figure>



