# Fields

An inventory item is made up of the following tabs and fields:

## General Information

* **Name**
  * The name of the inventory.
* **SKU **

  * The unique SKU of the inventory.

* **Slug**

  * The unique identifier which appears in the address bar.

* **Description**

  * The description of the inventory.
  * _Note_: Unlike before, do not enter inventory-specific features/specification such as rating, voltage, year, cost, etc. in the inventory description. There is a new tab called `Specification` that contains all the products features. This allows the product to be searchable and comparable to other inventory. 

* **Parent item **

  * The parent item of the inventory item.
  * Does this inventory item belong to another inventory item? For example, imagine you had a parent inventory of `Car` already, and you were adding a `Steering Wheel` inventory item, you would select `Car` are the parent item, this would result in the `Steering Wheel` being displayed on the `Car` inventory page.

* **Category**

  * The category the inventory item belongs to.

## **Images**

Drag and drop any/all inventory pictures in the dashed upload box. Alternatively, click the dashed upload box and manually browse for the images on your computed. Select which images you wish to upload. Images are automatically uploaded. Delete an uploaded image by clicking the red `X` next to the image.

## **Files**

Similar to `Images` above, drag and drop files \(files only - no images\). Files are automatically uploaded. Delete an uploaded file by clicking the red `X` next to the file.

## Stock

An inventory can have 1 single stock, or it can have 10x 1000 stock. All stock is monitored, and its movements are logged. If you move/add/delete/change a quantity or location \(row/section\), the application will log the before and after of the movement.

* **Quantity**

  * Inventory quantity in that location

* **Row**

  * Row where the inventory is currently stored

* **Section**

  * Section which the inventory is currently stored.

## **Specification**

As briefly discussed in the `Description` section above, the specification section is used to list an inventory items individual features/specification/facets. Basically, anything unique to that inventory which a potential customer would look for. For example: Voltage, Weight, Width, Cost, Year Made, Year Built, Cycles, are all specifications which a customer would like to now. A specification can be anything which is important to that particular inventory item.

* **Icon**

  * We use a icon library which allows us to use a variety of different icons on the site, icons which aid the user and improve the user experience.

  * All available icons can be found on the following page: [http://fontawesome.io/icons/](http://fontawesome.io/icons/). To use an icon for a specification, similar find an icon you wish to use. Click on the icon, and the page that loads, select the `fa-*` text as show in the example below:  
    ![](/assets/font-awesome.png)

* **Title**

  * You can either choose from an existing specification from the dropdown list, or begin to type your own. Once typed, be sure to click the new item as seen in the example below:  
    ![](/assets/add-new-specificaton.gif)

* **Content**

  * The value/content for that specification. I.e. If you're adding a voltage specification for a 12v battery inventory item, you'd enter `12v` for the content.



