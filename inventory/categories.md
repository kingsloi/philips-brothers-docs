# Categories

Categories serve as the navigation that appear underneath the `Inventory` page on the customer facing website, and ultimately allow the user to get to the right product quicker. 

Before adding any inventory, it's important to add the corrosponding categories first, as each inventory item will need a category. Categories can be added/updated/deleted at any time. 

* [Adding a Category](#adding-a-category)
* [Updating a Category](#updating-a-category)
* [Deleting a Category](#deleting-a-category)
* [Restoring a Category](#restoring-a-category)
* [Permanently Deleting a Category](#permanently-deleting-a-category)

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

## Updating a Category

To update a category:
* Navigate to {{ book.url }}/admin/inventory/categories/home.
* Choose the category you wish to edit from the list.
* Make whatever changes are necessary to the category.
* Click `Save`

### Default Details/Features/Facets 

To save the user time and rather than apply the same details (i.e. Voltage, Length, Height, etc.) to every inventory item, we've implemented default details for categories. What this means is that any inventory that's created in a category with default details, those `details` will be applied to the inventory. 

As an example, here's a category with 3 set default details:

1. Year
2. Cost
3. Voltage

When a user creates an inventory item in that category, those 3 details are automatically applied to the inventory item. The user will need to fill in the values for those details (or delete them if not necessary for that specific inventory item).

<figure>
    <img src="/assets/default-details.jpg"/>
    <figcaption>Default Details</figcaption>
</figure>

## Deleting a Category
Deleting a category which has inventory applied to it will **not** delete any inventory. Instead, any inventory assigned to that category will be reassigned to an `Uncategorized` category. 

To delete a category:
* Navigate to {{ book.url }}/admin/inventory/categories/home.
* Choose the category you wish to delete from the list.
* Scroll down to the `Danger Zone` in the `General` tab.
* Click `Delete`.
* Once prompted, confirm you do wish to delete the category.
* Click `Yes, delete it!`

## Restoring a Category
If a category has been deleted, it is not deleted permanently. Deleted categories will not be visible on the customer facing website, the search results, or in any of the admin sections. 

It is however possible to restore a category so that it is available once again. 

To do this:
* Navigate to {{ book.url }}/admin/inventory/categories/home.
* Directly above the table are two links to `All` and `Deleted`
* Click `Deleted`
* All deleted categories will appear here.
* Choose a deleted category from the list.
* Scroll down to the `Danger Zone` in the `General` tab.
* Click `Restore`.
* This category is now available for use again. 

**Note**: any inventory that was once associated to the deleted category will remain unchanged. 

## Permanently Deleting a Category
A category can only be permanently deleted if it has already been marked in active. 

To permanently delete a category:
* Follow steps above, however instead of clicking `Restore`, click `Permanently Delete`
* Once prompted, confirm you do wish to delete the category.
* Click `Yes, delete it!`
* The category will deleted permanently and no longer be restorable.










