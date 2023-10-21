
# Laptop Price Predictor

The Laptop Price Predictor is an advanced data-driven project designed to predict laptop prices based on a myriad of features. Leveraging the power of machine learning, specifically the Random Forest algorithm, this project aims to assist consumers, retailers, and manufacturers in understanding the factors that influence laptop prices in the market. Furthermore, the project has been deployed as a user-friendly web application using the Streamlit library, enabling seamless access for users.

# Methodology:
The project employs the Random Forest algorithm, a versatile ensemble learning method, to create a predictive model. Random Forests work by constructing multiple decision trees during training and outputting the average prediction of the individual trees for regression tasks. This approach enhances prediction accuracy and mitigates overfitting. The model has been integrated into a web application using the Streamlit library, which simplifies the process of transforming data insights into interactive web applications.

# Data Sources:
The project relies on a comprehensive dataset sourced from various sources, including online retailers, manufacturers' websites, and market research reports. This dataset encompasses a diverse range of laptops with detailed specifications, ensuring the model's adaptability and precision.

# Features:
The project considers an extensive array of features to predict laptop prices, including those mentioned earlier, such as RAM, processor speed, storage capacity, brand, screen size, operating system, and graphics card. These features are utilized by the Random Forest model to make accurate predictions about laptop prices.

# Implementation:
The project involves data preprocessing, feature selection, Random Forest model training, and deployment using the Python programming language. Libraries such as Pandas, NumPy, Scikit-Learn, and Streamlit are utilized to manipulate and analyze the data, create the machine learning model, and develop the user-friendly web interface.

# Deployment:
The project has been deployed as a web application using the Streamlit library. Streamlit simplifies the process of building interactive web applications for machine learning projects. Users can access the Laptop Price Predictor through a web browser, input the specifications of the laptop they are interested in, and receive accurate price predictions in real-time.

# How to run it on your pc:
### Prerequisites:

 * Python Installation: Ensure Python is installed on your system. You can download Python from python.org.

 * Git (Optional): If you prefer using Git, make sure it is installed. You can download Git from git-scm.com.

### Downloading the Project:

 * Using Git (Optional):
     * Open a terminal or command prompt.
     * Navigate to the directory where you want to clone the project.
     * Run the following command:
        
        ```
        git clone https://github.com/YourUsername/Laptop-Price-Predictor.git 
        ```
     * Change directory to the project folder:
         ``` 
         cd Laptop-Price-Predictor
         ```
 * Downloading as ZIP:
     * Click on the "Code" button and select "Download ZIP."
     * Extract the ZIP file to your desired location.

### Installing Dependencies:

 * Open a terminal or command prompt in the project directory.
 * Run the following command to install required Python packages:
    ```
    pip install -r requirements.txt
    ```

### Running the Application:

 * In the terminal or command prompt, ensure you are in the project directory.
 * Run the following command to start the Streamlit web application:
     ```
    streamlit run app.py
    ```
 * The application will start locally, and you'll see output indicating the address (usually http://localhost:8501).
 * Open your web browser and navigate to the provided address to access the Laptop Price Predictor web application.
 * Enter the laptop specifications as prompted and click on the prediction button to get the estimated price.

### Troubleshooting:

 * If you encounter any issues, please check the terminal or command prompt for error messages. Common problems include missing dependencies or incorrect Python versions.