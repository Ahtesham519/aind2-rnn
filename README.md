Meets Specifications
Great job getting everything all figured out and using the GPU. So much faster.

Project completed!
Heres a silly example of a huge dataset trained a bunch. A fellow Udacity student trained an RNN on the game of thrones book to generate the next chapters in the book.

https://motherboard.vice.com/en_us/article/evvq3n/game-of-thrones-winds-of-winter-neural-network

Chapters and code here.

https://github.com/zackthoutt/got-book-6/tree/master/generated-book-v1

Files Submitted
The submission includes all required file RNN_project_student_version.ipynb All code must be written ONLY in the TODO sections and no previous code should be modified.

Step 1: Implement a function to window time series
The submission returns the proper windowed version of input time series of proper dimension listed in the notebook.

Correct!

Step 2: Create a simple RNN model for regression
The submission constructs an RNN model in keras with LSTM module of dimension defined in the notebook.

Correct!

Step 3: Clean up a large text corpus
The submission removes all non-english / non-punctuation characters. (English characters should include string.ascii_lowercase and punctuation includes [' ', '!', ',', '.', ':', ';', '?'] (space, exclamation mark, comma, period, colon, semicolon, question mark))

Correct!

Step 4: Implement a function to window a large text corpus
The submission returns the proper windowed version of input text of proper dimension listed in the notebook.

Correct!

Step 5: Create an RNN perform multiclass
The submission constructs an RNN model in keras with LSTM module of dimension defined in the notebook.

Correct!

Step 6: Generate text using a fully trained RNN
The submission presents examples of generated text from a trained RNN module. The majority of this generated text should consist of real english words.

Doesn't make any sense but definitely mostly English.

input chars = 
er, of dubious and questionable memory. i had seen little of holmes lately. my marriage had drifted "

predicted chars = 
up to his hands and soncedsed to excemp to senverate of the stragge and the corners from the oncthor"

-------------------

input chars = 
f the singular tragedy of the atkinson brothers at trincomalee, and finally of the mission which he "

predicted chars = 
had deen to be absolutely sill. i should thr winding a can fine in the matter a lettle men whe could"

-------------------

input chars = 
ands clasped behind him. to me, who knew his every mood and habit, his attitude and manner told thei"

predicted chars = 
r as for more, and we have ne woll to get the street and a can of conders that i would gome all we h"








# Recurrent Neural Networks course project: time series prediction and text generation

### Amazon Web Services

Instead of training your model on a local CPU (or GPU), you could use Amazon Web Services to launch an EC2 GPU instance.  Please refer to the Udacity instructions in your classroom for setting up a GPU instance for this project.  [link for AIND students](https://classroom.udacity.com/nanodegrees/nd889/parts/16cf5df5-73f0-4afa-93a9-de5974257236/modules/53b2a19e-4e29-4ae7-aaf2-33d195dbdeba/lessons/2df3b94c-4f09-476a-8397-e8841b147f84/project)


## Rubric items

#### Files Submitted

| Criteria       		|     Meets Specifications	        			            | 
|:---------------------:|:---------------------------------------------------------:| 
| Submission Files      |  RNN_project.ipynb, my_answers.py --> both the completed notebook  RNN_project.ipynb as well as all completed python functions requested in the main notebook RNN_project.ipynb (TODO items) should be copied into this python script and submitted for grading.		|

#### Step 1:  Implement a function to window time series
| Criteria       		|     Meets Specifications	        			            | 
|:---------------------:|:---------------------------------------------------------:| 
| Window time series data. |  The submission returns the proper windowed version of input time series of proper dimension listed in the notebook.  |


#### Step 2: Create a simple RNN model using keras to perform regression

| Criteria       		|     Meets Specifications	        			            | 
|:---------------------:|:---------------------------------------------------------:| 
| Build an RNN model to perform regression. |  The submission constructs an RNN model in keras with LSTM module of dimension defined in the notebook.        |


#### Step 3: Clean up a large text corpus

| Criteria       		|     Meets Specifications	        			            | 
|:---------------------:|:---------------------------------------------------------:| 
| Find and remove all non-english or punctuation characters from input text data.  The submission removes all non-english / non-punctuation characters.  |


#### Step 4: Implement a function to window a large text corpus

| Criteria       		|     Meets Specifications	        			            | 
|:---------------------:|:---------------------------------------------------------:| 
| Implement a function to window input text data| The submission returns the proper windowed version of input text of proper dimension listed in the notebook.  |


#### Step 5: Create a simple RNN model using keras to perform multiclass classification

| Criteria       		|     Meets Specifications	        			            | 
|:---------------------:|:---------------------------------------------------------:| 
| Build an RNN model to perform multiclass classification. |  The submission constructs an RNN model in keras with LSTM module of dimension defined in the notebook.        |


#### Step 6: Generate text using a fully trained RNN model and a variety of input sequences
| Criteria       		|     Meets Specifications	        			            | 
|:---------------------:|:---------------------------------------------------------:| 
| Generate text using a trained RNN classifier.   | The submission presents examples of generated text from a trained RNN module.  The majority of this generated text should consist of real english words. |

## Submission
Before submitting your solution to a reviewer, you are required to submit your project to Udacity's Project Assistant, which will provide some initial feedback.  

The setup is simple.  If you have not installed the client tool already, then you may do so with the command `pip install udacity-pa`.  

To submit your code to the project assistant, run `udacity submit` from within the top-level directory of this project.  You will be prompted for a username and password.  If you login using google or facebook, visit [this link](https://project-assistant.udacity.com/auth_tokens/jwt_login) for alternate login instructions.

This process will create a zipfile in your top-level directory named rnn-<id>.zip.  This is the file that you should submit to the Udacity reviews system.
