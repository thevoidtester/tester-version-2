# tester-version-2
this is a second test

# Bingo!
![Purse](bH.png)
this is a online bingo game. Here is the data diagram:

## Team
Name | Email | Phone
--- | --- | ---
John | j@example.com | (887) 657 - 2323
Lem | l@example.com | (636) 736- 8576

# APIs 
[Join Game](README.md#join-game)

[Pay Anti](README.md#anti-up)

[Draw cards](README.md#draw-cards)

##Join Game!
This api allows the user to join the game.It uses the "GET' HTTP method

~~~http
http://bingo.com/api/joingame?name=matt
~~~

This allows a player named Matt to join the game.

Sample Response:
~~~javascrtip
{"status":"success"}
~~~

Sample Error:
~~~javascript

{"status":"fale"}
~~~
