food
///WANTS
// _WANT TO ADD CALORIES GOALS
//DEDUCT FROM THE CALORIES_

//1. Log a food eaten in a day by submitting a form w/ food name, calories & details.
// 2. View a list of foods I have logged.
// 3. Options to view all foods,
// only high-calorie foods (less than 500 calories)
// or only lower-calorie foods (less than 500 calories)
// 4. Click a food to edit its NAME, DETAILS, OR CALORIES.


1. need form to add food

2. need to view food

3. need to look at different category of food

4. need to edit food



***WISH
1. TO SEPARATE INTO MEALS category like bk, lunch, dinner, drink, snacks- fruit

2. Add Calorie that right for you

properties:
Age; weight; height; Gender; Goal: want to - maintain weight, loose weight, gain weight; See my calorie Goal
***


///food.model///
export class Food {
  public highCal: boolean = false; //public highCal? = if this true, display

    constructor(
      public name: string,
      public calories: number, public details: string, public id: number) { }
}
