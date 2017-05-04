# Categories

Categories serve as the navigation that appear underneath the `Inventory` page on the customer facing website, and ultimately allow the user to get to the right product quicker.

Before adding any inventory, it's important to add the corrosponding categories first, as each inventory item will need a category. Categories can be added/updated/deleted at any time.

* [Adding a Category](#adding-a-category)
* [Updating a Category](#updating-a-category)
* [Deleting a Category](#deleting-a-category)

----

## Adding a Category

To add a category:
* Navigate to {{ book.url }}/admin/inventory/categories/home.
* Click `New`

<figure>
    <img src="/assets/add-category.png" height="400" />
    <figcaption>Add a Category Screen</figcaption>
</figure>

* Enter in the new category name first.
* The `slug` (what appears in the address bar) will be automatically generated.
* Does the category belong to another category? If so, select the parent category from the dropdown list.
* Do you want to publish this category? Only published categories show on the customer facing website.
* Click `New`

## Updating a Category

To update a category:
* Navigate to {{ book.url }}/admin/inventory/categories/home.
* Choose the category you wish to edit from the list.
* Make whatever changes are necessary to the category.
* Click `Save`

### Default Specification/Details/Features/Facets

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

For more information on adding specifications/details/features, [visit the specification section in the inventory chapter](/inventory/Inventory/fields.md#specification).


## Deleting a Category

__Note: The category will deleted permanently and not recoverable.__

Deleting a category which has inventory in it will **not** delete any inventory. Instead, any inventory assigned to that category will be reassigned to the `Uncategorized` category.

To delete a category:
* Navigate to {{ book.url }}/admin/inventory/categories/home.
* Choose the category you wish to delete from the list.
* Scroll down to the `Danger Zone` in the `General` tab.
* Click `Delete`.
* Once prompted, confirm you do wish to delete the category.
* Click `Yes, I'm sure`