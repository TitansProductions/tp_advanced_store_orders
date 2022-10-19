# TP Advanced Store Orders

## Summary
TP Advanced Store Orders is a custom script made for FiveM Roleplay Servers which allows the players to order food from any of the available stores and be delivered by their employees.

## Showcase (Screenshots & Video)

## Frameworks

We are currently supporting ESX & QBcore (Not possible for Standalone since jobs are required).
## Player Features

1) The players will be able to choose a store which is available (online) in the Main Page when an employee is in duty. By selecting a store, all the products will be displayed by their image, price or description and can be ordered by adding to the cart and continue to the purchase if the client has a valid account in My Account page.

2) The players will be able to set a store as favorite in the Main Page and the favorite stores will be displayed in the My Account page as mentioned below.

3) The players will be able to see their Orders History page with all the requirement information about the store they purchased, such as Store Name, Order Details, Comments, Payment Type, Total Cost, Date & Order Id or even add a review. There is also an extra button to display more orders, the orders are displayed by x3.

4) The players who are employees (in job) of an available store, they will be able to manage the orders. They will also be able to set an order as delivered once this delivery has been delivered to the client in order to not be in the list for no reason.

5) The players will be able to set or change their account information in the My Account page, such as Name, Lastname & Phone Number. Also, all the favorite stores will be displayed in this page.

## General Features

1) Locales for changing the UI Enviroment based on the language you are interested or your server is based on.
2) Clicking sound when interacting with the enviroment (Volume is configurable).
3) All the screen resolutions are supported.

## Commands & Keybinds

There is an option if you want the players to open the Store Orders UI with a command / keybind but i personally do not suggest it, only for testing. The purpose of this script is to be added by a developer in your server's phone script as a phone application or use our zones in order to open them from a place which has computer / laptop objects (still not the best solution).

## Zones

There is also an option in the config if someone wants to use locations for opening the store orders UI environment (such as a place with computers).

## For Developers

You can open the UI Enviroment by calling `tp_store_orders:openStoreOrdersEnviroment` (Client Side Event)
