# Fyle-Assingment-Tax-Calculator
- The tax calculation works based on this formula -
    - Overall income (after deductions) under 8 (≤) Lakhs is not taxed.
        - Ex - if Gross Annual Income + Extra Income - Deductions =  6 Lakhs, no tax
         ![Screenshot (162)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/ed8002f0-6a85-4799-8463-1754a1680d78)

        - if Gross Annual Income + Extra Income - Deductions =  9 Lakhs, tax
         
![Screenshot (163)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/c674a28c-959d-492f-9a75-49722afac13e)

    - Income over 8 (>) Lakhs, the amount over 8 Lakhs is taxed at
        - 30% for people with age < 40
        
![Screenshot (186)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/c88674d6-116e-49b0-855d-8913ad6ec31d)
![Screenshot (187)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/a7788d83-74da-497b-af6a-a1569f64c665)


        - 40% for people with age ≥ 40 but < 60
        
![Screenshot (188)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/efc94310-b325-43cb-96b3-b3630b5bb2c5)

![Screenshot (189)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/2dbc024a-2f85-46a0-8e17-01dcd7ec1706)

        - 10% for people with age ≥ 60
       
![Screenshot (190)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/76203e36-77e0-49a6-9388-5ba2a223b0ed)
![Screenshot (191)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/b1e0905d-c0c1-4b99-a6ef-92758dab7920)


        - Example
            - Age = 34, Income = 40 Lakhs, no deductions, tax = .3 * (40 - 8) = .3 * 32 = 9.6 Lakhs
![Screenshot (196)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/db6a09c3-9bad-4a73-b8fa-7b1c728fa366)
    ![Screenshot (197)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/47bb2f6c-aacc-4f33-9d36-2e8127c1a4be)              

- Do not restrict user from entering incorrect values like characters in the number fields  
    - Highlight a error icon to the right of the input field (shown as an example in above image as a circle with `!`). Hovering over it should show the error in a tooltip
      ![Screenshot (155)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/8479a429-e7cc-474e-8080-5b22bddb65f1)
![Screenshot (160)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/92b14392-4fd0-4517-9720-ae2664fa920a)
![Screenshot (159)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/471ffaad-95fc-4f01-95cc-c10bd5bb07c1)
![Screenshot (158)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/2211d69e-22b4-4576-b95c-3bc68abd52ab)

    
     

    - If no errors are present, dont show the error icon
     ![Screenshot (165)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/cfd2688d-0364-4045-9437-44c2b6cde576)



    - This should be present in all the number fields
![Screenshot (173)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/697e66ae-15a6-4ccd-b150-4799a4d4d6a3)
![Screenshot (181)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/2bf3011b-a8a5-478d-8889-3e61900a4121)


    
- The age dropdown field should have 3 values
  ![Screenshot (177)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/e27eeb54-fbc6-4331-b458-5630cf9cd09a)

    - <40
![Screenshot (178)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/fd12a89d-80d6-492b-83f8-7859db8420f2)

     
    - ≥ 40 & < 60

     ![Screenshot (179)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/8ad66d61-ed55-41e7-9c64-f48308283309)

    - ≥ 60
    - ![Screenshot (180)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/b81e4728-51f3-472e-94a3-e98587141c89)



    - If user has not entered this value and clicks on submit, show a error icon hovering over which should show that input field is mandatory
  ![Screenshot (185)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/dd74ac55-bd5d-4cc2-b5c1-cca85dca020d)
![Screenshot (184)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/7f85747d-0d2e-483a-adf6-7fcae106133f)
![Screenshot (183)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/061e7155-0038-4205-b37c-b555850a1588)
![Screenshot (182)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/d60df377-5751-440f-a023-418b9e593b58)


- Error icons should not be visible in the form by default.
![Screenshot (139)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/081bad6e-9583-426a-a390-ce3413a0fdf3)


- Clicking on submit should show a modal which would show the final values based on above calculations
  ![Screenshot (166)](https://github.com/ankit142jaiswal/Fyle-Assingment-Tax-Calculator/assets/117927959/66a70567-6322-4e0b-85cd-d16892e1b6e8)



   


   



