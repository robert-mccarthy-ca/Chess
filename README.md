# Chess
My attempt at a chess app with AI.

I felt like getting some practice with machine learning and thought that chess would be a cool way to do it. This project can also be found on Kaggle at https://www.kaggle.com/robertmccarthy2/code. The rework is what will replace it once I get it done.

The point of this project is to create a chess app that saves the game state as a numpy array that i can then use to engineer some features for a classification model, asking the question of which move has the best chance that you win. No rules of chess for the AI, just given the set of legal moves that player can make, calculate which one has a better chance of winning, and take the best move. So to do that, I'm writing a chess game from scratch so it stores as a numpy array. Next up will be to parse and load in a buttload of games, fortunately there's no shortage of open source repositories of past chess games. After that, engineer my features, label my games, build my models and train away. Then test them. 

If I make it that far, I'll have learned something about machine learning, and then it'll be time to port it to Android and enable gaming over bluetooth. I just think it'd be cool to be able to take my chess app camping and play from my screened in hammock when the bugs are out, regardless of whether or not I have cell service. That it would have an AI opponent I built would just be icing on the cake.

As for progress, chess-from-first-principles-just-for-fun.ipynb contains my first run at this, it has the working chess game itself, but I was totally not happy with how the code looked and started rewriting it, and then started rewriting that attempt as well. I'm generally happy with the code in chess-rework.ipynb, I just have to finish it.
