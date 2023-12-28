# NexaBank Marketing Campaign Success Prediction

## Project Overview
Welcome to my Deep Learning project! This initiative focuses on enhancing the effectiveness of telemarketing campaigns using advanced deep learning techniques. The aim is to predict the success of our telemarketing efforts, offering insights into customer behavior and preferences, and thereby optimizing our marketing strategies.

## Objective
The primary goal is to build a sophisticated neural network using TensorFlow that can accurately predict the outcomes of our telemarketing campaigns. This model will serve as a cornerstone in our data-driven approach to customer engagement and business decision-making.

## Technologies Used
- **TensorFlow & Keras**: For building and training the deep learning model.
- **Pandas**: For data preprocessing and manipulation.
- **Matplotlib & Seaborn**: For data visualization and analysis.
- **Keras Tuner**: For optimizing the model’s hyperparameters.

## Dataset
The dataset (`bank-full.csv`) contains historical data from past telemarketing campaigns, which includes customer demographics, campaign details, and the campaign outcomes.

## Project Tasks
1. **Data Loading & Preliminary Inspection**: Using Pandas to load the data and inspect its structure and content.
2. **Exploratory Data Analysis (EDA)**: Utilizing Matplotlib and Seaborn to visualize data and discover patterns.
3. **Data Preprocessing**: One-hot encoding categorical features, scaling numerical features, and transforming the target variable.
4. **Model Building & Tuning**:
    - Constructing neural networks with TensorFlow.
    - Tuning models using Keras Tuner.
5. **Model Evaluation**:
    - Comparing model performance using metrics like precision, recall, F1 score, and AUC.
    - Visualizing training and validation loss, precision, recall, and AUC.
6. **Model Deployment**:
    - Saving the trained model for future use.

## Expected Outcomes
The project aims to deliver a model that not only predicts the outcomes of telemarketing campaigns but also provides deeper insights into how different customer segments respond to our marketing efforts. 

## Conclusion and Future Work
This model is expected to revolutionize NexaBank's marketing strategies, making them more data-driven and customer-centric. Future work may include integrating the model into our live marketing systems and continuously updating it with new data.

## How to Run
1. **Clone the Repository**: `git clone git@github.com:zakariahka/DeepLearningMarketingInsights.git`
3. **Install Dependencies**: `pip install -r requirements.txt`
4. **Run the Jupyter Notebooks**: Open and run the notebooks in order.

## Dataset Citation
This project uses the "Bank Marketing" dataset, which is publicly available for research purposes. The dataset was created by Paulo Cortez (University of Minho) and Sérgio Moro (ISCTE-IUL) in 2012 and has been widely used in the analysis of direct marketing campaigns by banking institutions. 

### Citation Details:
- Moro, S., Laureano, R., & Cortez, P. (2011). Using Data Mining for Bank Direct Marketing: An Application of the CRISP-DM Methodology. Proceedings of the European Simulation and Modelling Conference - ESM'2011, pp. 117-121, Guimarães, Portugal, October 2011. EUROSIS. Available at: 
  - [PDF](http://hdl.handle.net/1822/14838)
  - [BibTeX](http://www3.dsi.uminho.pt/pcortez/bib/2011-esm-1.txt)

### Dataset Description:
The dataset comprises direct marketing campaign data of a Portuguese banking institution. It includes detailed information about bank client data, campaign details, and the outcomes. The objective is to predict if a client will subscribe to a term deposit, making it a binary classification problem.

- **Dataset Files**:
  - `bank-full.csv`: Full dataset with all examples, ordered by date (from May 2008 to November 2010).
  - `bank.csv`: Subset containing 10% of the examples (4521 entries), randomly selected from `bank-full.csv`.

- **Attributes**:
  The dataset contains 16 input attributes, such as age, job type, marital status, education, etc., and one output attribute (target variable) indicating whether the client subscribed to a term deposit.

Please refer to the original publication by Moro et al. (2011) for further details and analysis of the dataset.

---