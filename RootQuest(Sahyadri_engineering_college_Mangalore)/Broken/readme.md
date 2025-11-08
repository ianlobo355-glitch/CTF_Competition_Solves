# Broken

## Challenge Description
![Challenge Description](images/description.png)

## Solution

In this challenge, We are given a file which could not be extracted.

I tried to extract using 7z tool, but still got an error

Finally, I used the xxd command to check the header of the file and VOILA!!! The flag was found. Also, yhe file header was not proper. Now I know why I cant open and extract the file.

![Login](images/DDLogin.png)
![LoginPassword](images/DDLoginPassword.png)

As we logged in, we are presented with a Dashboard with variety of items to shop from. I interacted with each item, and saw the output it gives. 

![Dashboard](images/DDDashboard.png)

I interacted with the page, clicking buy , which shows a page saying that i have purchased.

![Purchasedd](images/DDPurchased.png)

I then inspected the page to see what is flaw, and then found out that the code has a discount option which was hidden. Of course, as curious as I am, I changed the discount amount to 100 to make sure the purchased price will not be considered.

![Discount](images/DDDiscount.png)

I changed every items discount to 100 and clicked on every item to purchase. When i clicked on the "Golden Cookie", with the discount changed to 100, The flag was displayed.

![flag](images/DDFlag.png)


