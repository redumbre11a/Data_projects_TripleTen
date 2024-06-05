# TripleTen Sprint 15 Project - Computer Vision

The supermarket chain Good Seed would like to explore whether Data Science can help them adhere to alcohol laws by making sure they do not sell alcohol to people underage. You are asked to conduct that evaluation, keeping the following in mind:

- The shops are equipped with cameras in the checkout area which are triggered when a person is buying alcohol
- Computer vision methods can be used to determine age of a person from a photo
- The task then is to build and evaluate a model for verifying people's age
- To start working on the task, you'll have a set of photographs of people with their ages indicated.

## Data description

The dataset was obtained from ChaLearn Looking at People. It was prepared for the project and placed in the `/datasets/faces/` folder, there you can find

- The `final_files` folder with 7.6k photos
- The `labels.csv` file with labels, with two columns: `file_name` and `real_age`

## Your task
Perform the exploratory data analysis:
- Look at the dataset size.
- Explore the age distribution in the dataset.
- rint 10-15 photos for different ages on the screen to get an overall impression of the dataset.

Engineer a model to recognize a person's age through photographic analysis