[<img src="../assets/images/su-logo.png" alt="Skills Union Logo" height="80px" />](https://www.skillsunion.com/)

# Assignment

## Add the course model

From the work done, add the course model. Cohorts should be linked to a given course.

## Create 10 students, 2 cohorts and 1 course

You may want to have a look at [bulkSave](https://mongoosejs.com/docs/api/model.html#model_Model.bulkSave).

We want 10 (different) students - try to create them using a loop and possibly an [array of first names](https://gist.github.com/ruanbekker/a1506f06aa1df06c5a9501cb393626ea) (you can add/remove days/months/years to the birthDate too).

1 course 
- "Back end Java Script"
- Part of the Software Engineering curriculum
- Duration of 6 weeks

2 cohorts
- Put 5 students in each
- Cohort 1 starts 1/1/2022, second 1/3/2022

## Add a endDate method to Cohort

The endDate does not need to be saved as it can be computed, so we could have a endDate function:

- Take the start date
- Add the cours duration to it

## Query

- Read the [query](https://mongoosejs.com/docs/queries.html) chapter on Mongoose
- Use `findOne` to get the first cohort based on it's start date
- Use `find` to retreive all students from that cohorts (remember you have an id for that)
- Use `populate` to do both a once. Check how [Populate](https://mongoosejs.com/docs/populate.html) works