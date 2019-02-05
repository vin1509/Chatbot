# Chatbot-master

# Challenge:
Create a chatbot engine that will correctly respond to user input (greetings, queries, farewells). Some (limited) training data will be provided, as will canned responses for standard FAQs.

# Process:
Aggregate training data (see: first_clean.R)
Manually expand training set
Add greeting/farewell data
Classify inputs
Process training data (see: predict_response.R)
Clean, lemma/stem, tokens;n-grams
Compute proximity matrix for all tokens
Model (see: predict_response.R)
Pick a type of model/classifier to build off proximity matrix
Create one model per topic
Query (see: controller.R)
Predict (see: controller.R, predict_response.R)
Using models, classify new inputs
Select appropriate category or flag to query user for more information
Respond appropriately (see: controller.R)
Repeat 4:7 until "exit"

# To use:
Download and unzip the entire folder.
Set your working directory to the above folder (hint: setwd(</your/path/here>))
Type *source("controller.R")
Type controller()
Enter your query!
Repeat 4 and 5.
