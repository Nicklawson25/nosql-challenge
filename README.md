# nosql-challenge

Here’s a shortened version of the `README.md` that retains key instructions:

---

### README.md


# NoSQL Challenge: Eat Safe, Love

## Project Overview

This project involves setting up and analyzing UK food establishment data to support a food magazine, **Eat Safe, Love**, in identifying and rating food establishments across the UK.

## Setup Instructions

1. **Create and Clone Repository**:
   - Create a GitHub repository named `nosql-challenge`, clone it, and add the provided starter files.
   
2. **Database Setup**:
   - Use `NoSQL_setup_starter.ipynb` to import `establishments.json` into MongoDB.
   - Set up a database named `uk_food` and a collection called `establishments`.
   - Use `find_one` to verify the data import, and assign the collection to a variable for analysis.

3. **Database Modifications**:
   - Add a new halal restaurant to the database with the appropriate `BusinessTypeID` for “Restaurant/Cafe/Canteen.”
   - Delete any establishments within the "Dover" Local Authority.
   - Use `update_many` to convert `latitude`, `longitude`, and `RatingValue` fields to numeric formats.

4. **Analysis**:
   - Use `NoSQL_analysis_starter.ipynb` to answer these key questions:
     - Establishments with a hygiene score of 20.
     - Establishments in London with a `RatingValue` of 4 or higher.
     - The top 5 establishments with a `RatingValue` of 5, sorted by hygiene score, near "Penang Flavours."
     - The count of establishments with a hygiene score of 0, sorted by Local Authority.

For each query, display the document count, the first result, and a DataFrame with the top 10 rows.

## Submission
- Push your notebooks and the `establishments.json` dataset to GitHub. Include this `README.md` and ensure appropriate commit messages.

-
