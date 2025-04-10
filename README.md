<!-- hide -->
# Recommendation Systems - Your Future According to Data
<!-- endhide -->

This project aims to build a supervised classification model that, based on demographic and socioeconomic data of an adult (age, education level, occupation, marital status, country of origin, etc.), predicts whether the person will earn more or less than $50,000 per year.

Based on the model's results, students must develop an interpretative recommendation system capable of suggesting possible strategies or changes to increase the likelihood of surpassing that income threshold.

### Objectives

- Explore census data.
- Build socioeconomic profiles.
- Analyze the importance and weight of social variables (education, gender, race, etc.) in economic predictions.
- Apply recommendation system techniques.
- Visualize and professionally communicate findings.

## 🌱 How to start this project

Follow these instructions:

1. Create a new repository based on the [Machine Learning project template](https://github.com/4GeeksAcademy/machine-learning-python-template) [by clicking here](https://github.com/4GeeksAcademy/machine-learning-python-template/generate).
2. Open the newly created repository in Codespace using the [Codespace button extension](https://docs.github.com/en/codespaces/developing-in-codespaces/creating-a-codespace-for-a-repository#creating-a-codespace-for-a-repository).
3. Once the Codespace's VSCode has finished loading, start your project by following the instructions below.

## 📝 Instructions

1. Load the dataset. We will use the [Adult Income Dataset](https://archive.ics.uci.edu/dataset/2/adult), also known as **"Census Income"**. This information was collected by the U.S. Census Bureau and downloaded by the academy to store it in this project folder under the name `adult-census-income.csv`. Alternatively, you can load it directly in your code from the following link:

    ```text
    https://raw.githubusercontent.com/4GeeksAcademy/predicting-your-future-with-data/main/adult-census-income.csv
    ```

    This dataset includes variables such as:

    - Age
    - Education level
    - Marital status
    - Occupation
    - Hours worked per week
    - Gender
    - Country of origin
    - Annual income (>50K or <=50K)

2. Data preprocessing. Clean null or misencoded data, transform categorical variables, and normalize numerical variables.

3. Define the recommendation problem. Plan how you will structure your recommendation system:

    - What is being recommended?
    - Who is the "user" in this case?
    - What variables define a user's profile?

4. Build the recommendation system. Use one of the following approaches:

    - **Content-based filtering.** Represent each user as a vector and calculate similarities between users and recommendations.

    - **Collaborative filtering.** Simulate a user vs. trajectory matrix. Apply k-NN, Pearson correlation, or matrix factorization.

    - **Hybrid system.** Combine both approaches.

5. Test with simulated cases. Build simulated profiles of hypothetical users and observe what trajectories (education, occupation, etc.) the system would recommend to improve their estimated income.

    ```python
    # Example: 25-year-old user, high school graduate, works part-time
    user_profile = {...}
    ```

## 🚛 How to deliver this project

Once you have completed the practical case, make sure to commit your changes, push them to your repository, and go to 4Geeks.com to submit the repository link.
