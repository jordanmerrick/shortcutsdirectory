# Wishlist
    
Submitted by: [@melangue](https://github.com/melangue)

There is no wishlist functionality in iOS 11's AppStore.  
This workflow adds it back and then some.

Second, much improved version.

### Features
- Paginated list of your all your Wishlist apps (with icons)
- Works fully through the widget in the Notification Center
- Add apps straight from AppStore (also free ones) by using `Share sheet / Run Workflow` action, or copy the link to the clipboard and run it from Notification Center
- Remove App [Menu] - Self explanatory
- Check Prices [Menu] - Compare prices of all apps in your list and see if any of them is currently on sale

Pagination functionality was implemented from [/u/Neurogram](https://www.reddit.com/user/Neurogram)'s workflow.

On first run it will create a text file on your iCloud Drive which will act as the database of your apps.

You can change the region and currency in the first dictionary action.  
If you live in a country which puts the currency sign after the amount you can change that order in the first text block underneath the dictionary.