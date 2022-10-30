# Test cases

#### Preconditions:

- [Website](https://www.hugoboss.com/uk/men/)

## Test case 1: region selection

1. `Click on the region button `
2. `Click on current region”`
3. `Сhoose a new region`
4. `Click on the apply button`

**Expected result:** region will change.

## Test case 2: Adding item to the bag.

1. `Open link on the item`
2. `Select the size`
3. `Click "Add to Shopping Bag"`
4. `Click symbol of bag`

**Expected result:** The chosen item with all selected atributes is in the bag.

## Test case 3: Adding item to the bag but with other size.

1. `Open link on the item`
2. `Select the size`
3. `Click "Add to Shopping Bag"`
4. `Select a different size`
5. `Click "Add to Shopping Bag"`
6. `Click symbol of bag`

## Test case 4: Removing item from the bag

1. `Click symbol of bag`
2. `Click "cross"`

**Expected result:** The chosen item is removed from the bag.

## Test case 5: Select size

1. `Open link on the item`
2. `Select the size`

**Expected result:** If the selected size is available, it is displayed above the buy button, and if the selected size is not available, a window will appear in which you must enter the mail to which a notification will be sent when the product appears

## Test case 6: find a store

1. `Click symbol of marker`
2. `click on the field to enter the location`
3. `Enter location`
4. `Сhoose store type`


**Expected result:** store markers appear on the map that correspond to the selected parameters.

## Test case 7:Adding item to the bag without selected size.

1. `Open link on the item`
2. `Try to click "Add to Shopping Bag"`

**Expected result:** a window with a size selection will open.

## Test case 8: Viewing empty bag

1. `Click bag icon`

**Expected result:** The message "Your shopping bag is currently empty" is displayed.

## Test case 9: Searching for an item

1. `Click search icon`
2. `Type your keyword in search bar`

**Expected result:** Possible variants of products with this keyword are displayed.

## Test case 10: Adding a product to the wishlist

1. `select the section you are interested in`
2. `click on the heart icon located on the product picture`
3. `click on the heart icon`

**Expected result:** The product you marked should appear in your wish list.
