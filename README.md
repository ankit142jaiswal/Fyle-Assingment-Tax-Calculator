# Fyle-Assingment-Tax-Calculator
- The tax calculation works based on this formula -
    - Overall income (after deductions) under 8 (≤) Lakhs is not taxed.
        - Ex - if Gross Annual Income + Extra Income - Deductions =  6 Lakhs, no tax
          ![Screenshot (162)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/acec1c58-9e66-4505-8fe8-e92aeefd3878)

        - if Gross Annual Income + Extra Income - Deductions =  9 Lakhs, tax
          ![Screenshot (163)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/0fec6552-93b7-4e50-a987-0bca584e485b)

    - Income over 8 (>) Lakhs, the amount over 8 Lakhs is taxed at
        - 30% for people with age < 40
        - ![Screenshot (187)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/8d1e4822-cad4-4b42-aae1-e517bcf71616)
![Screenshot (186)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/b7c54fde-b680-43ed-9e45-306ad91e9f7f)

        - 40% for people with age ≥ 40 but < 60
        - ![Screenshot (189)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/7ad09513-119c-47ae-8eaa-94c9ca3b1da7)
![Screenshot (188)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/b06a757d-042d-4f06-899e-94e988e1d8d1)

        - 10% for people with age ≥ 60
        - ![Screenshot (191)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/7dd59230-f233-4c0a-8e72-7641e18bf1eb)
![Screenshot (190)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/136ae6c9-b985-4ad1-8f49-dd66cea48e3d)

        - Example
            - Age = 34, Income = 40 Lakhs, no deductions, tax = .3 * (40 - 8) = .3 * 32 = 9.6 Lakhs
    ![Screenshot (196)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/c426d748-fe0c-410b-b82b-68d5de0aa903)
Output:
![Screenshot (197)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/4fd72ac4-36f0-48fa-8f4f-10badec04636)

              

- Do not restrict user from entering incorrect values like characters in the number fields
    - Highlight a error icon to the right of the input field (shown as an example in above image as a circle with `!`). Hovering over it should show the error in a tooltip
    
      ![Screenshot (155)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/ea7ffdd0-fd97-45e5-b09b-d2dad98ccf0e)
![Screenshot (160)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/562d2fa1-56de-4a17-8c9d-bc41262dd9bc)
![Screenshot (159)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/7a3ca372-412e-4277-9a0b-5132394d72a7)

![Screenshot (158)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/e745ab8a-cccb-4b24-973e-9a536a08bd8f)

    - If no errors are present, dont show the error icon
   ![Screenshot (165)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/6d34f178-f78e-4bf5-9ea7-6678e468066f)


    - This should be present in all the number fields

![Screenshot (173)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/1eb4b063-d77b-40f4-8837-399654c69f66)
![Screenshot (181)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/b32c88f3-b7eb-4505-a693-54ea0674bd0e)

  

    
- The age dropdown field should have 3 values -
      ![Screenshot (177)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/8d16de5a-8d7c-4494-8327-f0623f3102de)
    - <40

      ![Screenshot (178)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/f41f4bd9-1869-47ad-9db1-e10db6fd29f5)
    - ≥ 40 & < 60

      ![Screenshot (179)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/90110249-1fac-46c3-9018-67e4e7e67b62)
    - ≥ 60
![Screenshot (180)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/762560b3-019b-4782-a75b-0d9e6a877359)

    - If user has not entered this value and clicks on submit, show a error icon hovering over which should show that input field is mandatory
     ![Screenshot (184)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/4812612a-4917-421f-bb07-61e852433b0c)
![Screenshot (183)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/2962ddd3-06d8-403a-9f0d-9bdc3ce673f2)
![Screenshot (182)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/9d34e3ba-527f-4449-a3a2-980e51bd7acf)
![Screenshot (185)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/0ff9e3a3-ee43-45a9-af0d-1ed9d2fc425f)


- Error icons should not be visible in the form by default.
  ![Screenshot (139)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/473c8d8b-7ca6-471e-a6cb-6482e4b308e9)

- Clicking on submit should show a modal which would show the final values based on above calculations
![Screenshot (166)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/d7b1dbb9-11a6-42c7-9949-84cc4d795052)



   


   



