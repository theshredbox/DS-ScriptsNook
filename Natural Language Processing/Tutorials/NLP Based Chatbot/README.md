## **PROJECT TITLE**
NLP based Chatbot.

## **INTRODUCTION**
In this tutorial we will be using Open AI's GPT-2 model. Microsoft’s DialoGPT was added to the Transformers model collection, DialoGPT is a GPT-2 model.

## **PURPOSE**
Aim of this tutorial is to make an AI chatbot with minimum need of resourses using the power of transformers.

## **BRIEF EXPLANATION**
In this tutorial, I will be explaining how to create a virtual character whose statements will be based on a transcript of character/show we'll choose. You can use characters and Shows of your choice. We will add a code to convert a regular text file with dialogs into a format that the model understands.

## **WORKING CONDITIONS**
<ol>
    <li><strong> Mounting the drive </strong></li> </br>
    Mount the drive and enter the path to the folder where your dataset is stored, so you can access it. </br>
  <img src="https://github.com/DevIncept-Contribution-Program-21/DS-ScriptsNook/blob/main/Natural%20Language%20Processing/Tutorials/NLP%20Based%20Chatbot/Images/Mounting.jpeg" width=700>
</div>
    <li><strong> Importing Packages and Installing transformer </strong></li> </br>
    Importing all the packages needed for the further processing of the model.
    <img src="https://github.com/DevIncept-Contribution-Program-21/DS-ScriptsNook/blob/main/Natural%20Language%20Processing/Tutorials/NLP%20Based%20Chatbot/Images/libraries.jpeg" width=700>
</div> </br>
    Instead of training from scratch, we will load "Microsoft's pre-trained GPT DialoGPT-small" model which is just over 351 MBs in size still performs pretty good, and fine-tune it using our dataset.
  <img src="https://github.com/DevIncept-Contribution-Program-21/DS-ScriptsNook/blob/main/Natural%20Language%20Processing/Tutorials/NLP%20Based%20Chatbot/Images/Transformer.jpeg" width=700>
</div>
    <li><strong> Setting up the arguments </strong></li> </br>
    Then we set up the required parameters which will be used to train the model. Eg: tokenizer_name, block_size, learning_rate, num_train_epochs, etc. </br>
  <img src="https://github.com/DevIncept-Contribution-Program-21/DS-ScriptsNook/blob/main/Natural%20Language%20Processing/Tutorials/NLP%20Based%20Chatbot/Images/Arguments.jpeg" width=700>
</div>
    <li><strong> Data Visualization </strong></li> </br>
    We then, take a look at first 10 columns of our original dataset. </br>
  <img src="https://github.com/DevIncept-Contribution-Program-21/DS-ScriptsNook/blob/main/Natural%20Language%20Processing/Tutorials/NLP%20Based%20Chatbot/Images/Data%20Vis1.jpeg" width=700>
</div>
    <li><strong> Data Processing </strong></li> </br>
    Once the data visualization is done, Now we will convert our dataset in a format suitable for our model. Basically we will concatenate responses in one string for each row (additionally we will add special ‘end of string’ token between responses, so the model will understand the end of each response in a string). </br>
  <img src="https://github.com/DevIncept-Contribution-Program-21/DS-ScriptsNook/blob/main/Natural%20Language%20Processing/Tutorials/NLP%20Based%20Chatbot/Images/Data%20Processing.jpeg" width=700>
</div>
    <li><strong> Training the data </strong></li> </br>
    Now its time to train our model, we need not to worry further as we have given the data in correct format to the model. </br>
  <img src="https://github.com/DevIncept-Contribution-Program-21/DS-ScriptsNook/blob/main/Natural%20Language%20Processing/Tutorials/NLP%20Based%20Chatbot/Images/Train.jpeg" width=700>
</div>
    <li><strong> Testing the model </strong></li> </br>
    After thae training process, the model is ready, now you can chat with the bot who is Rick in our case. Here is the conversation output of the chat with Rickbot. </br>
  <img src="https://github.com/DevIncept-Contribution-Program-21/DS-ScriptsNook/blob/main/Natural%20Language%20Processing/Tutorials/NLP%20Based%20Chatbot/Images/Test.jpeg" width=700>
</div>
</ol>

## **USAGE**
- Chatbots are helpful in guiding the user in an application or a website.

## **USE CASES**
Such chatbots can be trained and then pushed to hosting services like HuggingFace and can be implemented on the apps and websites.

## **LIBRARIES USED**
- Pandas
- Numpy
- Torch
- sklearn
- tqdm.notebook
- transformers
- TensorboardX

## **ADVANTAGES**
- Fun to use.
- Small size transformer model.
- Still gives better accuracy.

## **DISADVANTAGES**
- Can be heavy to train on high epochs.
- Underfitting can be issue if trained on low epochs.

## **APPLICATIONS**
Can be used for user guidance: 
- Applications
- Websites

## **CONCLUSION**
Congo! Your virtual Rickbot is ready! With the help of fine-tuning our model on a small dataset, we were able to create a virtual character with whom we can have interesting dialogs.
Here is an example of the chat: </br>

<img src="https://github.com/DevIncept-Contribution-Program-21/DS-ScriptsNook/blob/main/Natural%20Language%20Processing/Tutorials/NLP%20Based%20Chatbot/Images/ex1.jpeg" width=700>
</div>
</ol>

<img src="https://github.com/DevIncept-Contribution-Program-21/DS-ScriptsNook/blob/main/Natural%20Language%20Processing/Tutorials/NLP%20Based%20Chatbot/Images/ex2.jpeg" width=700>
</div>
</ol>


Using the given approach you can create many interesting virtual characters based on an arbitrary dialogs dataset (just a csv file with replicas, one replica per line). </br>
**Remember the better you use the dataset and fine-tune the parameters like learning_rate, num_train_epochs, block_size better the model will perform.**

## **REFERENCES**
- [Dataset Used](https://www.kaggle.com/andradaolteanu/rickmorty-scripts)
- [Sentiment Analysis](https://www.kaggle.com/andradaolteanu/sentiment-analysis-rick-and-morty-scripts/)
- [Similar Video Tutorial](https://www.youtube.com/watch?v=UBwvFuTC1ZE&t=3s)

## **YOUR NAME**

Hey, This is Hrugved Kolhe.

<a href="https://github.com/hrugved06"><img src="https://avatars.githubusercontent.com/u/59966943?s=400&u=445f4a7598547c0ecdeb22a265dd1a3dad9e297d&v=4" width="100px;" alt=""/><br /><sub><b> Hrugved Kolhe</b></sub></a>
</br>

[![GitHub followers](https://img.shields.io/github/followers/hrugved06.svg?label=Follow%20@hrugved06&style=social)](https://github.com/hrugved06)  [![Twitter Follow](https://img.shields.io/twitter/follow/HrugVed_?style=social)](https://twitter.com/HrugVed_)

</br>
<hr style="height:2px;#8080ffborder-width:0;border-radius: 5px;color:gray;background-color:#8080ff">
</br>
