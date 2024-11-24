java c
Software Development: Programming and Algorithms (SDPA) 
2024/25
Formave Assessment Feedback assessment is focused on helping students to develop their skills, knowledge and understanding of the  material. Formave assessment will not contribute to your mark. Guidelines are as follows:
•    Deadline: 13:00 (UK Bme) on Monday, 28 October 2024.
•   Submission: Details to be provided.
•   Advice: Develop your answers incrementally. To perform. a complicated task, break it up into steps, perform. each step on a diﬀerent line, give a new name to each result, and check that each intermediate result is what you expect.
General instrucons: 
Subming your work For submiNng your work, you will need to submit a zip ﬁle with the name formaQed as _. For example  “jp16127_ EMATM0048.zip”.   The zip ﬁle should contain all the python scripts necessary to run your program.
Feedback 
Your feedback will be based on both correctness and style.
• Correctness: How well the program works according to speciﬁca1ons. How good is the quality of your analysis.
• Style: The quality of the code and documentaBon.Your code should be well-wriQen and well-commented. You are encouraged to format your code per Python style. guidelines (hQps://www.python.org/dev/peps/pep-0008/). It should be clear enough for another programmer, such as the course staﬀ, to understand and modify it if needed. Quality code is expected to meet our style. requirements:
•    Every funcBon wriQen is commented, in your own words, using a docstring format that describes its behaviour, parameters, returns, and highlights any special cases.
•   There is a comment at the top of each code ﬁle you write with your name, secBon, and a brief descripBon of what that program does.
Software Development Instrucons
You will design, implement, test, and debug a text-based Greek restaurant simulaBon.This simulaBon must be text-based and will not have a graphical user interface; hence it is not allowed to use turtle, pygame, tkinter or any other API or external library for implementaBon. Only python standard libraries (see below link) can be used.
hQps://docs.python.org/3/library/
Task overview A restaurant has food that customers can purchase.   Each order requires prompBng the user to select what food and drink they want to order.    You should take the order of 3 customers and then summarise the orders and代 写Software Development: Programming and Algorithms (SDPA) 2024/25Python
代做程序编程语言 how much proﬁt was made.
A.   The restaurant sells the following food.Food                            Cost Per Order  Price per Order Gyro Chicken 6.25 7.50 Gyro Vegan 6.15 8.25 
B.   The restaurant sells the following drinks.Drinks Cost Per Order Price per Order Water 0.25 0.00 Soda 0.50 1.50 
C.   For each order:
a.   Prompt the user to select which food they want to purchase.
b.   Prompt the user to select which drink they want to purchase.
c.    Display the total price of the order to the user, then prompt for the next order. D.  Aher taking the orders, display the total proﬁt made.
Task speciﬁcaons 
• Errors and excepons handling Since you are taking user input, your code will need to handle potenBal errors.   Most errors occur in Null values and non-numeric inputs. Make sure you handle these errors. Your program should conBnue to run when given invalid input.   Examples of errors to be handled:
o No input
o Non-numeric
o Invalid range (e.g. negaBve values)
Example Run: Below is an example of how to interact and what you expect from the basic version of your text-based simulaBon.  You may use diﬀerent messages and output, just be sure that it is user friendly and meets the requirements.
python3 main.py
Please select your food and drink for order 1
Please enter number for food selection
1 Gyro Chicken
2 Gyro Vegan
>>> thisisastrnotanumber
Invalid integer thisisastrnotanumber: Please enter a valid integer.
Please enter number for food selection
1 Gyro Chicken
2 Gyro Vegan
>>> -1
Invalid range -1: Please enter a value between [1, 2]
Please enter number for food selection
1 Gyro Chicken
2 Gyro Vegan
>>> 1
Please enter number for drink selection
1 Water
2 Soda
>>> 1
Order 1 was Gyro Chicken with a Water, price 7.50
Please select your food and drink for order 2
Please enter number for food selection
1 Gyro Chicken
2 Gyro Vegan
>>> 1
Please enter number for drink selection
1 Water
2 Soda
>>> 2
Order 2 was Gyro Chicken with a Soda, price 9.00
Please select your food and drink for order 3
Please enter number for food selection
1 Gyro Chicken
2 Gyro Vegan
>>> 2
Please enter number for drink selection
1 Water
2 Soda
>>> 2
Order 3 was Gyro Vegan with a Soda, price 9.75
Total profit 6.35

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
