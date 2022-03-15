# BMI-body_mass_index-_calculator
find your BMI score
height=float(input("Enter your height in meters : "))
weight=int(input("Enter your weight in kgs    : "))

BMI=round(weight/(height*height))
print(BMI)  #Body Mass Index
if BMI >=35:
    print(f"your BMI is {BMI},clinically obese")
elif BMI >30:
    print(f"your BMI is {BMI},obese")
elif BMI >25:
    print(f"your BMI is {BMI},slightly overweight")
elif BMI >18.5:
    print(f"your BMI is {BMI},normal weight")
else:
    print(f"your BMI is {BMI},underweight")
