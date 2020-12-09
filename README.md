# Gender_Prediction

#Introduction:-
A Natural Language Processing model trained with over 1,00,000 (1 Lakh) names is used to predict a gender of a person based on the first name of the person.This model is created using Long Short Term Memory(LSTM) a variant of Recurrent Nueral Network and tested over 11,000 samples with a test accuracy of 85% which is quite high in nlp for out of sample test cases.



#Local Installation
Drop a ⭐ on the Github Repository.
Clone the Repo by going to your local Git Client and pushing in the command:

https://github.com/ksdkamesh99/Ling.git

    Install the Packages:

pip install -r requirements.txt

    At last, Go to 3.7 Python interpreter(Make Sure to create virtual env).

#Import Ling as l in any python file/Interpreter(note it is present in the same directory)
import Ling as l
print(l.gender("kamesh"))
# Output will be 1 which means male
print(l.gender("sudha"))
#Output will be 0 which means female
