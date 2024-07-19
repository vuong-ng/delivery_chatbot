## Default Welcome Intent

Text response:  Hello, How can I help you? You can say "New Order" or "Track Order"
				Good day! What can I do for you today? You can say "New Order" or "Track Order"
				Greetings! How can I assist? You can say "New Order" or "Track Order"

				
## Default Fallback Intent

Text Response:  I didn't understand. You can say 'New Order' or 'Track Order'. 
				Also, in a new order, please mention only items from our available menu: California Roll, Spicy Tuna Roll, Philadelphia Roll, Vegetable Roll, Salmon Sashimi, and Dragon Roll . Also specify a quantity for each item for example: "One Spicy Tuna Roll, and one vegetable roll"				


## Intent= new.order

new order
Place new order

	Text Response = 
		Ok, starting a new order. You can say things like "I want two california roll and a salmon sashimi". Make sure to specify a quantity for every food item! Also, we have only the following items on our menu: California Roll, Spicy Tuna Roll, Philadelphia Roll, Vegetable Roll, Salmon Sashimi, and Dragon Roll.

		Starting new order. Specify food items and quantities. For example, you can say, "I would like to order two california rolls and a salmon sashimi. Also, we have only the following items on our menu: California Roll, Spicy Tuna Roll, Philadelphia Roll, Vegetable Roll, Salmon Sashimi, and Dragon Roll.

## Intent= order.add - context: ongoing-order

Give me 2 California Rolls, and a Philadelphia Roll.
I'd like to order two plates of spicy tuna roll,  one california roll, and one dragon roll, please.
Can you please get me two servings of spicy tuna roll, one salmon sashimi, and one dragon roll?
Please prepare 2 portions of philadelphia roll, along with one spicy tuna roll and 1 sashimi for me
2 california rolls, 3 dragon rolls, 1 vegetable roll.
Can I get 2 plates of vegetable rolls, along with one california roll and 1 dragon roll?
I'll take 2 orders of Philadelphia roll , one Cali roll, and 1 dragon roll, if you don't mind
I want 1 salmon sashimi, 2 spicy tuna roll and one , do it fast plz
In addition, add a salmon sashimi and 2 dragon rolls
Moreover, include 2 spicy tuna rolls
Also, please give me one dragon roll
Additionally, I'd like 2 dragon rolls.
1 sashimi and ok lets add one dragon roll too
3 cali rolls
Oh yes, add one spicy tuna roll as well

## Intent= order.complete - context: ongoing-order

Nope
That's all I needed
Done ordering it
Place an order
Done
That's it

## Intent= order.remove - context: ongoing-order

No sashimi and dragon roll in my order. please remove.
Take dragon roll and cali roll off the order, please.
I'd like to exclude sashimi and dragon roll, please
I no longer want the tuna roll in my order, please remove it
Exclude the sashimi from my order
I would like to remove the pizza from my order
Please take the pizza off my order
delete dragon roll from my order
hey, plz get rid of dragon roll and sashimi
I don't want vegetable roll
remove salmon from my order
can you remove salmon?

## Intent= track.order

check the status of my order
track order
track existing order

### Text response:
	Definitely. What is your order id?
	Sure. Please enter your order id.
	Definitely. What is your order id?


## Intent= track.order - context: ongoing-tracking

how about 32
how about 40?
here it is - 63321
here you go: 123
here is my order number 675
id is 453
here is my order id # 341
7890
123
345
