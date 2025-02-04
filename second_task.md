# Task 2

##  Take the college input to the user

```
def get_college_name():
    approved_colleges = ["icfai university", "manipal", "amity university"]  # Correct spelling in lowercase
    while True:
        college_name = input("Enter your college name: ").strip().lower()  # Convert input to lowercase
        if college_name in approved_colleges:  # Compare with lowercase list
            return college_name
        print("Invalid college name. Please try again.")


college = get_college_name()
print(f"College selected: {college}")
```

### Output:

- This code give the `college_name` which is enter by the user if the college name is validate it automatically go the user inside my data if it is not validate it not go my data and give the message to the user invalid college name please try again.

#### Learning

- Make the this code i learn about how to define function, how to take input, how to use built method to make the code more readable and understandable.
