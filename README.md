# Vistula_sprong_controller

This is the main class that starts our Spring Boot application

![image](https://github.com/user-attachments/assets/6807116b-afbc-468c-9cd1-c72a528b9c40)


Controller annotation marks this as a web controller and returns HTML views

Method hello()
Handles HTTP GET requests to the root path, It returns a string but only when there is @RestController
String won`t show itself in a @Controller

Method greeting()
Handles GET requests to /greeting.
Accepts an optional name parameter from the URL
If no name is provided, it defaults to "World"
![image](https://github.com/user-attachments/assets/2ed2dbe1-405b-4555-84fe-e1f5872f6063)



It’s a Thymeleaf template
Displays a sample paragraph and loads the image from /static/Vistula.jpg
![image](https://github.com/user-attachments/assets/d51f916d-f027-495d-b3aa-0b6fbe7ef63d)


Examples of code and webpage how programm works:
![image](https://github.com/user-attachments/assets/ce24a2a5-c5c5-4aca-a27b-74b65f94c998)

![image](https://github.com/user-attachments/assets/da765415-c219-4791-af17-31cfe9f84cfe)

