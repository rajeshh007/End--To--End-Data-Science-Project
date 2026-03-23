# End--To--End-Data-Science-Project

company name: CodeTech IT solutions

Name : Rajesh R

domain : Data Science

duration: 4 Weeks

Intern ID : CTIS6705

mentor : Neela Santosh

descprition of the task :

This project demonstrates the development of a simple machine learning web application using Flask for predicting salaries based on years of experience. It integrates model training and deployment, showcasing how machine learning models can be used in real-world applications.

The project consists of two main parts: model creation and web application deployment. In the first part, a dataset named salary.csv is loaded using the Pandas library. This dataset contains two columns: experience (independent variable) and salary (dependent variable). The data is then separated into input features (X) and target output (y), where experience is used to predict salary.

A Linear Regression model from Scikit-learn is used to train the data. Linear Regression is a simple and widely used algorithm for predicting continuous values. The model learns the relationship between experience and salary by fitting a straight line to the data. Once trained, the model is saved using the Pickle library as a file named model.pkl. This step is important because it allows the trained model to be reused later without retraining.

In the second part, a web application is created using the Flask framework. Flask is a lightweight web framework in Python that allows easy integration of machine learning models into web interfaces. The saved model (model.pkl) is loaded into the Flask application using Pickle.

The application defines two routes. The first route ("/") serves as the home page and displays a simple HTML form. This form allows the user to input their years of experience. When the user submits the form, the data is sent to the second route ("/predict") using the POST method.

In the "/predict" route, the input value entered by the user is retrieved using request.form. The value is converted into a float and passed to the trained model for prediction. The model then calculates the predicted salary based on the given experience. The result is displayed back to the user in a simple text format.

The application is run using app.run(debug=True), which enables debugging and automatically reloads the server when changes are made to the code. This is useful during development.

One important aspect to consider is the file path used for loading the model. Proper path formatting (using raw strings or forward slashes) ensures that the file is correctly located and loaded without errors.

Overall, this project illustrates the complete workflow of a machine learning application—from data loading and model training to deployment using a web interface. It highlights how simple models can be integrated into user-friendly applications, making predictions accessible to non-technical users.

This project serves as a strong foundation for more advanced applications, such as adding multiple input features, improving the user interface, or deploying the app online using cloud platforms.

output of the task :
<img width="78" height="21" alt="Image" src="https://github.com/user-attachments/assets/f0c55e28-92fa-4830-9c1d-8efde17d4e55" />

<img width="625" height="46" alt="Image" src="https://github.com/user-attachments/assets/bcf5bb01-456c-4946-9589-81c8b9486242" />
<img width="747" height="141" alt="Image" src="https://github.com/user-attachments/assets/9433cb9c-687c-45f5-9497-a63f20aa4f35" />
<img width="518" height="154" alt="Image" src="https://github.com/user-attachments/assets/81b55a25-d2a8-470c-825a-cfe896b63491" />
<img width="448" height="70" alt="Image" src="https://github.com/user-attachments/assets/f8b71a3e-842b-456a-ac12-47174d34802f" />

