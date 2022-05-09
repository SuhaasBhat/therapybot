# therapybot
Therapy chatbot project for GENED1179

The testing notebook is Test Therapy Chatbot.ipynb - this is where you can try out the chatbot yourself.
In theory, the only packages you need to install are transformers and pytorch (as well as jupyter, of course). It's possible that you'll need some others, but I don't think you will, unless you want to run the training as well (though you'll want a GPU for that).

The dataset is found in dataset.csv. 
The training notebook is therapy_bot_causalML_train.ipynb.
The models are in small_model and large_model. 

This chatbot is a fine tuned DialoGPT, built with the help of this [excellent tutorial](https://nathancooper.io/i-am-a-nerd/chatbot/deep-learning/gpt2/2020/05/12/chatbot-part-1.html), which supplied most of the boilerplate training code for the project. [This implementation](https://colab.research.google.com/drive/15wa925dj7jvdvrz8_z3vU7btqAFQLVlG#scrollTo=ezq6Qtl_3NtD) of that tutorial also provided a lot of help. 
