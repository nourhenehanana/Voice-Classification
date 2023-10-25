# Voice-Classification
Deploy machine learning model to classify male and female voice based on data features using support vector machines (SVM) as it is highly effective to discern complex patterns  between the acoustic features such as spectracl characteristics that are crucial for distinguishing between male and female voices. Also SVM in our case excels at finding optimal decision boundaries that help at defining the correct output in this binary context. 

# Steps for modeling 

- Label Encoding the output
- Perform data scaling and check for missing values
- Build the SVM, then calculate itsaccuracy which achieved 0.9737
- Perform Grid Search to find the optimal kernel and fine tuning the SVM hyperparameters in order to improve the model's accuracy = 0.978
