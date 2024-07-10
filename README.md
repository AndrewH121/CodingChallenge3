# CodingChallenge3

Objective: This exercise will test your knowledge of loops and arrays by enhancing your theoretical app with a feature that handles user reviews, calculates statistics, and performs actions based on review data.

Step 1: Copy Over Coding Challenge Solution 2 to a new Swift file in a separate repository named "Coding Challenge Solution 3".

Step 2: Implement the following features in your new file:

*Part 1: Handling User Reviews*
Create an Array of Reviews:
- Declare an array userReviews to store individual review ratings (Double). Assume ratings are between 1.0 to 5.0.
- Assign initial values to this array representing past user reviews.

Calculate Average Rating:
- Use a for loop to iterate through the userReviews array and calculate the average rating.
- Print the average rating with descriptive text.

Part 2: Adding New Reviews
Simulate Adding New Reviews:

Use a while loop to simulate adding 5 new user reviews to the userReviews array.
Each iteration should prompt the user (simulated by assigning values in code) to input a new review rating and add it to the array.
Recalculate and Print Average Rating:

After adding the new reviews, recalculate the average rating using a for loop.
Print the updated average rating with descriptive text.

Part 3: Performing Actions Based on Review Data
Count Reviews by Rating:

Use a for loop to count how many reviews fall into different rating categories:
Excellent (4.5 to 5.0)
Good (3.5 to 4.4)
Average (2.5 to 3.4)
Poor (1.0 to 2.4)
Print the count of reviews in each category with descriptive text.
Determine Overall Recommendation:

Use a conditional statement based on the new average rating to update the recommendation variable (as per Coding Challenge 2).
Print the new recommendation with descriptive text.


Part 4: Consolidating Reviews and Feedback
Store Positive and Negative Feedback:

Declare two arrays positiveFeedback and negativeFeedback to store comments (String) on positive and negative reviews respectively.
Simulate adding comments to these arrays based on the review ratings (e.g., if a review rating is 4.0 or higher, add a comment to positiveFeedback; otherwise, add it to negativeFeedback).
Print Feedback Summary:

Use a for loop to print out all positive and negative comments with descriptive text.
Summary of Tasks:

Create and initialize an array for user reviews.
Calculate and print the average rating using a for loop.
Simulate adding new reviews using a while loop and recalculate the average rating.
Count and print the number of reviews in each rating category.
Update and print the overall recommendation based on the new average rating.
Store and print positive and negative feedback comments using arrays and loops.
By completing this challenge, students will demonstrate their understanding of arrays, loops, conditional statements, and how to integrate these concepts into a cohesive program.
