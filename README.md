# CODTECH-Task-1
      Project :- Password strength checker
      Name :- Mekala Hemanth
      Company :- CODTECH IT SOLUTIONS
      ID :- CT08PD775
      Domain :- Cyber Security & Ethical Hacking
      Duration :- May to june 2024
      Mentor :- SRAVANI GOUNI

Explanation of the Code
Length Check:

Passwords of 12 or more characters receive the highest score for length.
Passwords between 8 and 11 characters receive a moderate score.
Passwords shorter than 8 characters receive no points for length.
Complexity Checks:

We use regular expressions to check for the presence of uppercase letters, lowercase letters, numbers, and special characters. Each category adds to the score if present.
Uniqueness Check:

We check if all characters in the password are unique (no repeating characters).
Strength Summarization:

Based on the total score, we classify the password strength as Strong, Medium, or Weak.
Usage
To use the tool, simply call the assess_password_strength function with the password you want to evaluate. The function returns a dictionary containing the strength score and feedback.

Feel free to customize the scoring and feedback mechanisms to better suit specific requirements or add more checks as needed.

output:-
![Screenshot 2024-06-19 091856](https://github.com/hemanth-mudhiraj-55/CODTECH-Task-1/assets/168768041/17b3a797-ffff-42da-92da-ff89ae856532)

