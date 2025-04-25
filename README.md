### IDAI107--2405460--Pravar--2405744--Zivantika--2405728--Aashi

# Future Eats 


### Project Overview

*Future Eats is a project that aims to develop a smart assistant powered by Generative AI tailored for people to enhance sustainability in daily operations, creating new recipes, Planning new events, generating personalised dishes, testing and increasing your knowledge by answering cooking quiz and getting to know about many new dishes. The assistant will interactively help people through key areas such as food waste reduction and sustainable sourcing. The system will provide actionable insights, personalized suggestions, and highlight best practices in environmental stewardship. The primary objective is to support chefs and other people in making data-driven decisions that lead to improved sustainability performance, cost efficiency, generating new recipes and alignment with global green standards.*

### Link for UI and UX of the app:

https://www.motiff.com/proto/mmwQKM6G62IEa16Wkszfq5p?nodeId=205%3A259&pageId=0%3A1&startingPointNodeId=205%3A259&scaling=min-zoom "Capstone UI and UX by Pravar Golecha"

*(Note: The app may not look similar to the UI and UX due the some limitations of streamlit and other things.)*

### Key Features and Functionalities

*Future Eats integrates a variety of powerful AI-driven features to support and enhance restaurant operations holistically. Below are the key functionalities elaborated:*


#### Leftover Management:

*Managing food waste effectively is crucial for both cost control and sustainability. This feature will help the people to:*

*- Monitor leftover food quantities and categories (e.g., cooked meals, raw ingredients).*

*- Identify patterns to minimize overproduction and optimize portion sizes.*

*-Recommend creative ways to repurpose leftovers into new dishes (e.g., turning day-old bread into croutons or using vegetable scraps for broths).*

*- Adjust future ingredient orders based on leftover data to reduce waste.*


#### AI-Powered Recipe Creation:

*Leveraging generative AI, the assistant can:*

*- Create new and innovative recipes based on available ingredients, cuisine type, dietary needs, and customer preferences.*

*- Suggest fusion ideas or seasonal recipes to add variety to the menu.*

*- Optimize recipes for cost, nutritional value, and sustainability (e.g., low carbon footprint dishes).*


#### Beverage Generation:

*- Offers trending cocktails, mocktails, smoothies, and health drinks using AI-curated ingredient combinations.*

*- Uses available ingredients in the inventory to create low-waste, cost-effective beverages.*

*- Simply input the available ingredients (e.g., lemon, mint, soda, honey), and the assistant will generate unique beverage recipes like a Mint Honey Sparkler.*


#### Ingredient-Based Dessert Generator:

*- Input available ingredients (e.g., milk, banana, oats, honey) and get unique dessert ideas like Honey Banana Oat Cups or No-Bake Banana Pudding.*

*- Offers both quick and elaborate recipes based on available time or occasion.*

*- Provides easy-to-follow instructions with quantities, prep/cook time, serving suggestions.*


#### Event Planning:

*The assistant aids in planning themed dining events, sustainability awareness weeks, seasonal promotions, and more by:*

*- Generating event concepts and content.*

*- Providing marketing ideas, invitations, and social media captions.*

*- Offering tailored menu suggestions for each event theme.*


#### Achievements:

*- The user recives badges when the task is completed.*

*- The achievements are unlocked when the user has completed the task.*


#### Friends & Networking:

*- People can add other users as friends to share insights, sustainability strategies, and recipe ideas.*

*- Collaborate on food trends, sustainable practices, and industry innovations.*

*- Work together to achieve sustainability goals and improve your knowledge.*


#### Personalized Dish Recommendations:

*The system can interact with managers to understand customer preferences and:*

*- Generate dish ideas tailored to specific customer profiles or dietary needs (e.g., vegan, gluten-free, keto).*

*- Use customer feedback or sales data to adapt dishes and recommend improvements.*


#### Cooking Knowledge Quiz and Learning Module

*- Fun, interactive cooking quizzes to test and build culinary knowledge.*

*- Fact cards and trivia about global cuisines, unique ingredients, and cooking techniques.*


#### Profile:

*A profile which saves your data of:*

*- The number of recipes generated and the details of recipe.*

*- The number of leftover's added and the recipe generated form it.*

*- The events planned by user and the details of the event*

*- The number of quiz questions attempted, user's accuracy on the basis of the correct and wron answers you gave also it saves the total number of correct answers user gave* 

*- The number of friends athe user has.*

*- The ranking of a user among all the user's and the friends of the user on the basis of the points and achivements.*


### Technologies Used

#### Programming Languages:

*- Python (primary language)*

#### Frameworks:

*- Streamlit (Web application framework)*

#### Libraries:

*1) Data Manipulation & Analysis:*

*- pandas (pd) - Data manipulation and analysis*

*- datetime - Date and time handling*

*2) Visualization:*

*- plotly.express (px) - Interactive data visualization*

*-plotly.graph_objects (go) - Low-level visualization*

*3) AI/ML:*

*- google.generativeai - Google's Generative AI API key (Gemini 1.5 pro)*

*4) Standard Libraries*

*- json - JSON data handling*

*- os - Operating system interface*

*- random - Random number generation*

*5) Custom Modules:*

*- User_Data (UserDataManager) - Custom module for user data managemen*

*The rest of the requirements of the project are in the requirements.txt*

### Installation Instructions for FutureEats App

#### Prerequisites

*- Python 3.7 or higher must be installed on your system*

*- Visual Studio Code (VS Code) is recommended as the IDE*

#### Step by Step instructions 

*- Step 1- Create a new directory for the project by running the following commands in terminal:*

mkdir FutureEats
cd FutureEats

*- Step 2- Create and activate a virtual environment by running:*

On Windows:
python -m venv venv
.\venv\Scripts\activate

On macOS/Linux:
python3 -m venv venv
source venv/bin/activate

*- Step 3- Download the "requirements.txt" by running this command:*

pip install -r requirements.txt

*- Step 4- Replace the Gemini API key in the code with your own Gemini 1.5 pro API key from "Google Cloud Console".*

*- Step 5- Open "Command Prompt" and type "cd" for changing the dierectory and  then type the path of the dierectory where you have saved your all files of the "Future Eats" app, after that press "enter" and you will see that the dierectory has been changed.*

*- Step 6- Running the Application by using this command in Command Prompt:*

Streamlit run 8.py


#### Important Notes

*- Ensure all imports are working correctly.*

*- The app will open in your default web browser.*

*- Default port is typically: http://localhost:8501*

*- First-time users will need to register/sign up.*

*- Make sure you have stable internet connection for AI features.*


#### Troubleshooting

*- If packages are missing: pip install [package_name]*

*- If Streamlit isn't recognized: python -m streamlit run 8.py*

*- For permission errors: Run terminal as administrator.*


#### System Requirements

*- RAM: 4GB minimum, 8GB recommended.*

*- Storage: 500MB free space.*

*- Internet: Required for AI features.*

*- OS: Windows 10/11, MacOS, or Linux.*


### Usage Instructions for Future Eats

*- Once the app is running, the user needs to Sign Up first then after sign up the user needs to remeber his or her password and Username to Login whenever he/she opens the app.*

*- Once the user is Logged in then the user will see the dashboard of "Future Eats" where the user will see the: Menu Perfomance chart, Top Rated Dishes and the Inventory Status.*

*- The user will also see that on side bar there is the name of the app and its slogan. Also the user can see "Welcome, his/her name" and below it there are points of the user that how much points they have scored, below it there is an option of "Logout" which can used when the user wants to Logout. After, which there is an option of select feature.*

*- When the user clicks on that option then the user will a list of features which will lead the user to their respective pages when clicked. The Features are:*

*1) Dashboard*

*2) Profile*

*3) Recipe Suggestions*

*4) Leftover Management*

*5) Menu Personalization*

*6) Event Manager*

*7) Cooking Quiz*

*8) Beverage Generator*

*9) Desert Generator*


#### Features and Functioning of Profile:

*- On the top the user will see there name and below it there would be 3 section of "Total points, Quiz attempts and Quiz accuracy". These sections would display the user's Total points, Quiz attempts and Quiz accuracy as the user progresses.*

*- Then there will be a series of feature and fuction like:*

*1) Activity log- This feature will show the user about his/her acitivity history in an table format which will include date(with time), the action done at that paticular time and the points recived or reduced for that paticular activity.*

*2) Recipes- It will show the details of the recipe which would be generated by the user from the recipe suggestion feature.*

*3) Events- This feature will show the events generated by the user with event details.*

*4) Quiz Progress- This will show the user that the Total Questions Attempted by them and the Correct Answers given by them.*

*5) Leftover- It will show the recipes generated by the user from the Leftover feature.*

*6)  Achievements- This feature will show that how much auser has  Achieved and how much Availabe Achievements are still there for the user to achive.*

*7) Friends and Leaderboard- Here, the user will be able to add his friends by entering their username and the user will aslo be able to see the Leaderboard of the app which has all the user who have logged in or sign up in the app. the leaderboard will show the rankings of the user and the other user's on the basis of the achivements, points and quiz accuracy. Below it there will be a graph of the top 5 players/user's in the app.*

*8) Beverages- In this part we can see that how many beverages are generated by the user, then it also shows that what is the favorite type of beverage of the user, it shows that when was the last beverage created by the user and also it gives the details of the beverages created by user like the recipe of the bevrage, at what date and time the recipe for beverage was generated and a pie chart showing the distribution of beverage type.*

*9) Dessert- In this part we can see that how many desserts are generated by the user, then it also shows that what is the favorite type of dessert of the user, it shows that when was the last dessert created by the user and also it gives the details of the dessert created by user like the recipe of the dessert, at what date and time the recipe for dessert was generated and a pie chart showing the distribution of dessert type.*


#### Features and Functioning of Recipe Suggestion

*- In Recipe Suggestion there is a feature where we can search or add ingredients by typing there name and then press enter. Other option is that click on choose an option and select the ingredients from the options given and then click on generate recipe and then wait for sometime and then the recipe will be generated.*

*- Once you generate a recipe then 5 points will be added to the user's account.*

*- Note: If you are typing the ingredients then type all the ingredients in once and then click enter because when you enter the ingredients by typing one by pne then the previous one will be lost and then you need to enter it again.*


#### Features and Functioning of Leftover

*- Type the Ingredient name of the Leftover and then adjust the quantity of the leftover which is in grams and then click on Add ingredient button and it will create table which will consist the name of the leftover ingredient, its quantity and the date and time on which it was added.*

*- Once a leftover ingredient is added in the table then the user can more and more leftover ingredients and their quantity.*

*- O nce an leftover ingredient is added in the table then there will be an option of select ingredients and that option will contain the leftover ingredients added in the table.*

*- The user can choose any of them and it can be more than one.*

*- After choosing the leftovers then click on the generate recipe option and after few moments of waiting the recipe will be generated and it have the same quantity of leftover ingredients which the user had added.*

*- When the user has generated a Leftover recipe then the user is awarded with 5 points.*

#### Features and Functioning of Menu Personalization

*- In Personalized Menu Recommendations the user will add the Dietary Preferences and it can be done via typing the preferences or by choosing the preferences from the select preferences option.*

*- After chosing the dietary preferences the user needs to mention the Additional ingredients and this can be done by typing the ingredients or by selecting the ingredients and then click on the Generate personalized menu and it will be generated.*

*- When the user has generated a Personalized menu then the user is awarded with 5 points.*


#### Features and Functionting of Event Manager 

*- In event manager the user will need to fill the details which are asked in the Plan new event section in the event manager feature. The details include the event name, event date, event theme, dietary restirctions of the the event, number of guests, appetizzers, main course, beverages, dessert and estimated cost per person in ₹ (minimum cost is ₹200) and at last the user has to click on save event button and event will be saved.* 

*- The event will be saved in view events section in the event manager feature. When the user clicks on event then the user will be able to see the details of the event which the user had entered while planning the event.*

*- When the user has created or planned an Event then the user is  awarded with 5 points.*


#### Features and Functioning of Cooking Quiz

*- Cooking quiz is a section of the Future Eats which is a fun and educational feature designed to test and enhance the culinary knowledge of people.*

*- In quiz, the user needs to answer the questions by selecting the answer in MCQ format and then click on submit answer to know whether the user is correct or wrong. For every correct answer the user gets with 5 points and for every wrong answer the user loses 10 points.*


#### Features and Functioning of Beverage Generator

*- In the beverage recipe generator the user has to select the beverage type, ingredients in beverage, base liquid, flavor preferences, seasonal preferences, dietary restrictions and the user also can add the ingredients by typing the name of the ingredient. After filling this details the user has to click on the generate beverage recipe button.*

*- When the user has generated a beverage recipe then the user is  awarded with 5 points.*


#### Features and Functioning of Dessert Generator

*- In the Dessert recipe generator, the user has to select the dessert type, ingredients, cuisine type of the dessert, dietary restrictions, special preferences and the ingredients can also be added by typing. After filling or selecting the details, the user needs to click on generate dessert recipe which will generate the recipe for dessert.*

*- When the user has generated a dessert recipe then the user is  awarded with 5 points.*


### Acknowledgements 

*I would like to express our sincere gratitude to our mentor for her guidance throughout this capstone project.*

*Special thanks to OpenAI’s language models for powering the generative features of the application, Claude AI, Copilot AI, Google Cloud Console for providing Gemini API key, VS code and to resources such as GitHub, Motif, Figma, and Google Firebase for providing the tools and platforms used in the development process.*

#### *Lastely, I also acknowledge Pravar Golecha(myself) for making the whole project which includes the whole code for app which basically means whole the app, integrating Gemini 1.5 pro API key, UI and UX of the app, content for ppt, Making the whole Github Repositery(typing the whole content of repositery), Demo video of the app.*


### Link for the Demo Video of the app:

*(Note: The quality of the video maybe reduced due the link formation, so you can download the video from canva and see it better quality.)*

https://www.canva.com/design/DAGj1VhB5a4/_ztw0xnNVYB4W5fwk9c_pg/edit?utm_content=DAGj1VhB5a4&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton


## Link for FututeEats app:

https://future-eats-bypravargolecha.streamlit.app/

#### NOTE: Pls reload the stie or check the internet connection if the recipe is not loading.
