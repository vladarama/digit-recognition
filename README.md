# Handwritten Digit Recognition

This semester long machine learning research project was done as a part of the Introduction to Computer Programming course at Dawson College. 

### Research Question
A large obstacle that people nowadays may encounter is the digitalization of our daily lives. Let's take for example notetaking in class: some people may prefer to take notes by hand whilst others like to type their notes on their computer. However, what if there is a matter that would require both handwritten notes and digital notes? Would it not be a hassle to take notes on different mediums and make it confusing? This is where handwriting recognition would come into play and help by recognizing handwritten characters to digitalize them. Another example could be translation of words that were not written with the conventional characters or with unfamiliar characters from another language, wouldn't handwriting recognition help with this? Hell, if handwriting recognition could be refined to be more precise with the help of neural networks, modern technology could probably use handwriting recognition for cheating prevention purposes since it would allow for differentiation between different people's handwriting. The fundamentals of this computer ability can be done through machine learning, more precisely with the help of the Scikit learn library.

The question is simple; How accurately can machine learning, using Convolutional Neural Networks (CNN) predict and recognize handwriting compared to basic classification models from the scikit learn library (SVM, KNN, RFC).

### Our Classification Model
After a lot of research and analysis, we realized that creating a convolutional neural network would be the best solution to accurately classify handwritten digits. After optimizing our cnn model to achieve 99% accuracy, we decided to build a graphical user interface to test our model in real time. Below are a few screenshots of our drawings and the predictions made by our model. You can try it yourself by opening the colab file and running all cells.

![3](https://user-images.githubusercontent.com/86936229/208530517-1a7724da-0730-468b-abce-11b4c0f26a20.png)
![8](https://user-images.githubusercontent.com/86936229/208530522-0f8970a4-85b9-4c0e-85e9-02170715daf1.png)

### What I learned 
• Collaborated with two other teammates to complete this research project in time

• Learned how to implement different classification models from sklearn such as KNN, SVM and Random Forest Classifier

• Understood how to create a convolutional neural network (CNN) using TensorFlow and Keras

• Optimized the CNN model to achieve a 99% accuracy on the testing dataset

• Analysed the accuracy of our models by plotting graphs and tables using Seaborn and Matplotlib and by measuring different accuracy scores such as the f1-score

• Implemented a graphical user interface using Gradio that displays the model's predictions




