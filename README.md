# Amazon-Store-Data-Analysis-Best-Practice-Drawing-Business-Insights

Understand the reason for orders rejected and the likelihood of a new order being rejected. also provide recommendation that would help them to take necessary actions and subsequently reduce the loss.

# Data Dictionary¶
The Order data is provided in an excel file. The columns are: Independent Features:

order_no - Unique Amazon Order Number

order_date - Date on which the order was placed

buyer - Name of the buyer

ship_city - Delivery Address City

ship_state - Delivery Address State

sku - Unique identifier of a product

description - Product description

quantity - Number of units ordered

item_total - Total amount paid by the buyer

shipping_fee - Charges borne by Boss Leathers to ship the item

cod - Mode of payment: Cash on delivery or not

order_status - Status of the order


# Insights and Recommendations

1) % of order failure is more expected on cash on delivery items for 8.62 % more than Online payment items that comes wit 3.78% of failure
2) order success depend more on the Online payments as the % of order success for online is 96.22 and more than the cash on delivery orders 91.38
3) most of our successed sellings tend to be for online payments rather than cash on delivery
4) most of successed sellings happened on Dec 2021 for both online and cash on delivery payments
5) number of online payments increase over months till Dec 2021 then starts to decrease
6) for returned to seller items increase slowly untill reach its high volume on quantities returned on Nov 2021 by 5 quantities and then descrese
7) amounts sold increase on Dec 2021 specifically on wednesday
8) Amounts sold increased on the end of the week starts from thursday to friday
9) most of orders returned happend on Friday and sunday respectively
10) most of orders returned happend on November
11) fees by quantity returned in Online Payment is 52.44 and less than the fees by quantity returned in cash on delivery payments 80¶
12) it seems like New delhi has the highest quantity of orders returned by 4 quantities
13) also most of shipping fees for all cities are the same except for KOLKATA and GURUGRAM
14) DELHI has the highest quantites returned by 4 quantites but MAHARASHTRA has the highest ship_fee
15) MAHARASHTRA State have the most quantities of orders by 38 for 32 orders' ordered
16) the product" Women's Set of 5 Multicolor Pure Leather Single Lipstick Cases with Mirror, Handy and Compact Handcrafted Shantiniketan Block Printed Jewelry Boxes " have the most quantities sold by 41 products for 33 orders' ordered
17) sunday and thursday have the most quantities of products ordered by 31 products for both of them for 30 orders ordered on sunday and 29 orders ordered on thursday respectively
18) most of orders made on sunday, wednesday, and thursday respectively
19) the orders returned not depend on specific buyer
20) for SKU " SKU: DN-0WDX-VYOT " has the most shipping fees for returned Items for 3 from 11 returned orders
21) there are 3 SKUs returned to seller wihout any delivered orders, so we lost shipping fees for these SKUs
