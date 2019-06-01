# meal-box-tracker
Keep track of your prepped meal boxes - what you have in stock, their expedition date and other statuses.

## The Problem
Whenever you prep a box of food and store it in the fridge, it's difficult to keep track of when it expires. It might also be hard to keep track of which prepared meals you actually have in stock.

## The Solution
Label your meal boxes - either by some arbitrary ID or a QR code - and scan it with the mobile app. This will store it as a meal box item with certain properties - name, expiry date, contents and amount amongst others things. This way, you will be able to receive notifications when meals are close to expire. Also, you can plan your meals easier, knowing just what it is that you have in stock.  

## Architecture
* Mobile application (Xamarin?)
- Web API (ASP.NET Core)
- Web page (Blazor?)
- SQL Database (MYSQL/MariaDB?)
  - Entity Framework Core
