# BBallBooks
Beginning of a book keeping system for a basketball coach
1) Series of books (possibly the coach keeps one book for each year)
2) Each book has a series of 'leagues' (possibly girls/boys/age levels)
3) Each league has a series of games (two teams and a date)

If I would continue the project, each team has a list of players, and the coach can keep 
statistics on games, teams, and players. This would allow the coach to look up his/her
notes on the team/players before the game.

The interesting part of the code is:
1) it is MVC - with a "Navigator" being passed around. The Navigator keeps
currency (i.e. remember what book the user is working with while drilling into
leahttps://github.com/EfraimKrug/BBallBooks/blob/master/README.mdgues and games).

2) The Views (jFrames) pass commands to the command queue.

3) The command queue is processed in the MainApp.

4) The MainApp sets up the task and then calls the specific Navigator method.

If you have any comments how to make this better (not more complete or aesthetically pleasing)
I will be delighted to read them! Thanks...
