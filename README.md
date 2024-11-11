# OOP -Object-oriented Programming
Here's a `README.md` file for your Movie Rating application:

# 1. Movie Rating System

This Python program rates movies based on four parameters: story, actors, music, and cinematography. Using object-oriented programming (OOP), the `MovieRating` class calculates an overall rating and provides a verdict on the movie's quality (Excellent, Good, Average, or Poor) based on the calculated score.

## Features

- **Rating Parameters**: Each movie is rated on a scale from 0 to 10 for the following parameters:
  - **Story**
  - **Actors**
  - **Music**
  - **Cinematography**
- **Overall Rating Calculation**: An average score is calculated from the four parameters.
- **Verdict**: The program provides a verdict on the movie's quality based on the overall rating:
  - 8 or higher: **Excellent**
  - 6 to 7.9: **Good**
  - 4 to 5.9: **Average**
  - Below 4: **Poor**

## Code Overview

- **MovieRating Class**: 
  - `__init__`: Initializes the movie attributes, ensuring each rating is between 0 and 10.
  - `verdict`: Returns a verdict based on the overall rating.
- **Object Instantiation**: Four movie objects (`movie1`, `movie2`, `movie3`, `movie4`) are created with different ratings, and their verdicts and overall ratings are printed.

## Usage

1. **Create a MovieRating Object**: Instantiate a `MovieRating` object by providing the movie name and ratings for story, actors, music, and cinematography.
2. **Get Verdict**: Call the `verdict` method to obtain the movie's quality assessment.
3. **Check Overall Rating**: Access the `overall_rating` attribute to view the average rating.

### Example

```python
# Creating a MovieRating object
movie1 = MovieRating("Interstellar", 9, 10, 10, 9)

# Get the verdict
print(movie1.verdict())  # Output: Interstellar is Excellent

# Check the overall rating
print(movie1.overall_rating)  # Output: 9.5
```

_____________________________________________________________________________________________________________________________________________________________________________________________________________________

