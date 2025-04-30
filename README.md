Its a program to help you calculate what SGPA you require to achieve your target CGPA by the end of a specific semester. The credit distribution is as per 2023-2027 session for CSE given on jiit.ac.in website.
## IMPORTANT: If you are not in CSE 2027 graduating batch, you must modify the credits array according to your branch in source code to get accurate CGPA prediction. 
List of things updated in new commit as of 10th January 2025: 
1. UI Enhancements
The design was updated to look more professional.
Added a dark mode toggle to allow users to switch between light and dark themes.
Adjusted font and background colors in dark mode to ensure all elements are visible.
2. Dynamic Target SGPA Calculation
Replaced the fixed 6th and 8th semester SGPA output with a dynamic calculation for each remaining semester (e.g., 4th, 5th, 6th, etc.).
Added specific messages for each semester, showing the required SGPA to achieve the target CGPA.
3. Input Clarification and Validation
Changed current semester input to completed semesters for better clarity and user accuracy.
Added a warning note to ensure users correctly input the number of completed semesters.
Enhanced input validation to prevent invalid entries (e.g., CGPA outside 0-10, semesters outside 1-7).
4. Credit Adjustment
Updated the credit system to reflect 20 credits for the 4th semester (from 18 credits).
5. Achievability Check
Added logic to determine whether the target CGPA is achievable by the end of the 8th semester.
Displays a large red warning message, "You are cooked," if the target CGPA is mathematically unachievable.
Ensured intermediate semesters are still calculated even if the overall target is unachievable.
6. Improved User Feedback
Results now include clear explanations for each semester's required SGPA.
Shows "Impossible to achieve" only for semesters where the required SGPA exceeds 10, while still providing other data.
