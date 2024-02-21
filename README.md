# Introduction
Our project, an ecosystem for farmers, makes use of machine learning algorithms and sensor technology that can be used at any time and from any location to monitor and enhance critical environmental conditions that influence plant development. Our goal is to create a data-driven decision-making system that leverages real-time data on pH, water level, CO2 concentration, and light intensity to make timely suggestions for fertilization, irrigation, and other treatments .It employs machine learning models to improve crop output, resource efficiency, and sustainability in agriculture, paving the way for precision farming techniques that lead to increased green productivity.
Our approach tackles a number of significant issues in conventional agriculture, with a primary emphasis on increasing crop productivity and resource efficiency.Our approach reduces waste and promotes efficient water use to optimize resource utilization.The employment of sensors has automated the ongoing manual monitoring that a traditional system required.The overuse of fertilizers and pesticides is the primary problem that has been resolved.By accurately adjusting the input to the requirements of the plant, our technology reduces the environmental impact of agriculture and promotes sustainable agricultural methods.

The intelligent agricultural system project's future involves technology advancements, scalability, and broader outreach. Partnerships with research institutions, modular system adaptation to various crops, partnerships with agribusinesses, and cost optimization will make the solution more affordable for a wider range of farmers .By combining technology innovation with strategic collaborations, community participation, and a commitment to user success, we can broaden our intelligent agriculture system's reach and contribute to sustainable and efficient farming practices on a global scale.

The project combines sensor data collection, machine learning analysis, targeted interventions, and a feedback loop to enhance plant development and agricultural productivity. It employs vertical farming techniques to ensure sustainability. Farmers can access quantifiable data on plant parameters such as pH levels and water capacity through tools like cameras, sensors, and a mobile application. The implementation of the project has resulted in more controlled environmental conditions and improved crop development. Overall, this integration of advanced technologies promotes sustainable and efficient crop cultivation practices.


# Setting up IPython Notebook with Dataset

## Requirements
- Python installed on your system
- Jupyter Notebook installed (you can install it using pip: `pip install notebook`)

## Steps

1. **Clone the repository**:
   Clone the repository containing the IPython Notebook file and the dataset.
   git clone https://github.com/prashant-jadon/intelli-farm-model.git

2. **Navigate to the directory**:
   Navigate to the directory where you cloned the repository.
   cd intelli-farm-model

3. **Launch Jupyter Notebook**:
  Launch Jupyter Notebook from the terminal.
  jupyter notebook


4. **Open the IPython Notebook**:
In the Jupyter Notebook interface that opens in your web browser, navigate to the directory where the notebook file (`google_sol_v2.ipynb`) is located and click on it to open.

5. **Run the Notebook**:
Run the cells in the notebook to interact with the dataset and execute the code.

6. **Access the Dataset**:
Access the dataset `new_plant_data.csv` within the notebook using Python libraries like Pandas.

```python
import pandas as pd

# Load the dataset
df = pd.read_csv('new_plant_data.csv')

# Explore the dataset
print(df.head())
 ```


