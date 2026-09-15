# NutriCheck

## About NutriCheck
NutriCheck is a web-based nutrition tracking application that helps users calculate Body Mass Index (BMI), record daily food comsumption, and manage personal nutrition goals. 
There are 2 roles in NutriCheck, which are users (for the general public) and nutritionist.

### Users
- Exploring different foods with their nutritional information.
- Finding ideal nutrition based on their own BMI.
- Record daily food consumptions.
- Read articles provided by nutritionists.

### Nutritionist
- Providing food information to the system's database.
- Create articles related to food nutrition. They can also write recipes for an ideal diet.

## Our Goal
The main goals of this project are to:
- Make nutrition information easy to understand.
- Help users make more informed food choices.
- Present nutritional data in a simple and accessible way.
- Encourage healthy and balanced eating habits.

## Web Preview
### Dashboard
<img width="340" height="182" alt="image" src="https://github.com/user-attachments/assets/a418060f-4a8b-48e6-a5c2-8f8c9073e1d8" />

Gives a health or nutrition overview of the user's based on their food intakes. Also provides shortcuts to other features.

### Health Profile
<img width="334" height="173" alt="image" src="https://github.com/user-attachments/assets/c38a60da-3ace-4f4b-a484-25453f1b8916" />

Creates or updates the user's current BMI.

### Log Page
<img width="333" height="168" alt="image" src="https://github.com/user-attachments/assets/d88a67e8-c93d-4a2a-b1be-c3377fd8076c" />

Contains detailed information about the user’s food intake, including breakfast, lunch, dinner, and snacks. This page calculates and summarizes the total nutritional content of the foods consumed by the user.

### Food Catalouge
<img width="298" height="158" alt="image" src="https://github.com/user-attachments/assets/72019358-21d6-41ef-bf6a-0802b5aba453" />

A page to browse and add the user's daily food to the log page. It also acts as a food nutrition information filter. This filter can show users foods that match the nutritional content specified in the filter.

### Article
<img width="331" height="155" alt="image" src="https://github.com/user-attachments/assets/a5ff8c17-51f1-4a0e-8834-22fcd295a3ab" />

Provides articles from nutritionists. Users can read detailed information of various foods. Nutritionists may also write recipes for users to try.

## How to run it manually
1. Clone the repository
```bash
git clone https://github.com/aRandomUser1107/AOL_NutriCheck.git
```
2. Open the project
Navigate to the project folder:
```bash
cd nutrition-project
```
3. Run the website
run
```bash
npm install
npm run dev
```
### If you also want to try out the backend:
(Note: open a new terminal for this)
1. Navigate to the backend directory:
```bash
cd backend
```

2. Create and activate a virtual environment:
Windows:
```bash
python -m venv venv
venv\Scripts\activate
```
macOS/Linux:\
```bash
python3 -m venv venv
source venv/bin/activate
```
3. Install the dependencies:
```bash
pip install -r requirements.txt
```
4. Start the FastAPI development server:
```bash
uvicorn main:app --reload
```

## Documentation & Demo
For more info, check out our documentation!

(Note: the documentation is written in Bahasa Indonesia)

Documentation : [Project Report] (https://docs.google.com/document/d/1K02SmUzNpSwL0L6a7XWIYPY7s3ilEs4tlJ79FeMSlNc/edit?usp=drivesdk)

Demo (out of date): [NutriCheck] https://aol-nutri-check.vercel.app/ 
