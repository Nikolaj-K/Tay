# Tay
Trained GPT-2 bot on 4chan /pol/ shitposts.

120 MB 4chan.txt used to train the bot (Inside /src/ folder)

This is the trained model, on gpt-2.

10100 epochs, trained on google collab pro.

Edit TAY WORKING CODE.py with the folder location inside the script (the %cd jupiter command).

Try to run it on google collab or jupiter notebook.

If running directly on python, remove the lines starting with !pip which you need to run them on console, using python 3.5 (because gpt-2 uses tensorflow 1.15 and it can only be installed with pip from python 3.5)

The cannot find tensorflow.contrib error means you have tensorflow 2 which removed .contrib, you need tensorflow 1.15
