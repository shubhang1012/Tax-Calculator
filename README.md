# Tax-Calculator
# Tax-Calculator
This is a simple tax calculator implemented in JavaScript. It calculates the overall income after considering gross income, extra income, age group and deductions. Additionally, it provides validation for input fields.

## References & Requirements
- The tax calculation works based on this formula -
    - Overall income (after deductions) under 8 (≤) Lakhs is not taxed.
        - Ex - if Gross Annual Income + Extra Income - Deductions =  6 Lakhs, no tax
        - if Gross Annual Income + Extra Income - Deductions =  9 Lakhs, tax
    - Income over 8 (>) Lakhs, the amount over 8 Lakhs is taxed at
        - 30% for people with age < 40
        - 40% for people with age ≥ 40 but < 60
        - 10% for people with age ≥ 60
        - Example
            - Age = 34, Income = 40 Lakhs, no deductions, tax = .3 * (40 - 8) = .3 * 32 = 9.6 Lakhs
- Do not restrict the user from entering incorrect values like characters in the number fields
    - Highlight an error icon to the right of the input field (shown as an example in the above image as a circle with `!`). Hovering over it should show the error in a tooltip
    - If no errors are present, don't show the error icon
    - This should be present in all the number fields
- The age dropdown field should have 3 values -
    - <40
    - ≥ 40 & < 60
    - ≥ 60
    - If the user has not entered this value and clicks on submit, show an error icon hovering over which should show that the input field is mandatory
- Error icons should not be visible in the form by default.
- Clicking on submit should show a modal which would show the final values based on the above calculations.
# Assumptions
- Input validation occurs during focus, change, and submit button click events. Error messages are displayed under these conditions:-
    - Typing a negative number prompts "Please enter non-negative values."
    - Leaving a field empty when clicking submit or focusing on a field and not typing anything prompts "This field is mandatory."
    - Typing anything other than numbers prompts "Please enter numeric values only."
  - The total sum of the income is the sum of gross annual income and extra annual income . The tax calculated is on the total sum of the income only.

# How to run the webpage locally 
- To run your application locally, you can follow these simple steps:
   - Begin by downloading all the necessary HTML, CSS, and JavaScript files to your computer.
   - Open the files in a code editor and run the files in a web browser .
   - Since we are using bootstrap maintain a good network connection .
   - Once the files have succesfully executed you can use the tax calculator easily.

  # Web Page Snippets.
  ![image](https://github.com/shubhang1012/Tax-Calculator/assets/73165623/a34772e3-95a6-4f26-a21e-1aa11d771238)
  ![image](https://github.com/shubhang1012/Tax-Calculator/assets/73165623/5216a50a-c654-40ae-adc6-5d947dd8de1a)
  ![image](https://github.com/shubhang1012/Tax-Calculator/assets/73165623/32f1806e-f538-4433-ab0c-ff98eebf2c94)
  ![image](https://github.com/shubhang1012/Tax-Calculator/assets/73165623/99a04165-7c3c-4dd5-b832-a5410138272f)
  ![image](https://github.com/shubhang1012/Tax-Calculator/assets/73165623/c98c17b5-3757-4105-a717-b91b1a1b168f)






  



