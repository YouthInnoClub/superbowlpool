# superbowlpool
Super bowl pool game in Python

Super Bowl Squares Pool. Arguably, this is the most common type of football office pool, one you've probably seen before and perhaps even participated in. Squares Pools and Super Bowl Pools are almost synonymous. The pool is displayed on a grid of squares with numbers along both the top and left side of the page. (source from The Legal Risk Of Super Bowl Squares Pools - Forbes
https://www.forbes.com/forbes/welcome/?toURL=https://www.forbes.com/sites/marcedelman/2014/01/31/the-legal-risk-of-super-bowl-squares-pools/&refURL=https://www.google.com/&referrer=https://www.google.com/)

Our goal is to design and implement a Python based superbowl pool game, so it can be played remotely without physically present.

This game was designed to host a Super Bowl Pool game with friends from multiple remote sites, so it has some basic requirements.

1. should be 10 by 10 grids (with one more row and one more column for score)

2. should only allow one player to choose the grids at one time, and the lock period should no more than 5 minutes (so the pool will not be locked by one person accidentally)

3. should refresh and show the updated grids in real time (with reasonable latency, such as 2 seconds)

4. each player should able to use its name for bid (choose the grids)

5. automatically track the grids, and one grid can only be placed by one player, the pool will close when it was filled up

Besides those basic requirement, we will have some advanced features, include (but not limited to):

1. template can be changed

2. send email to player after it finish the bid

3. setup the limitation for how many grids can be choosed by one players

We will start to post the code when we have our initial release, and hopefully, we can play the real Super Bowl Pool game using our own designed Python game next year. All comments or suggestions are welcome.
