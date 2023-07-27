<h1 align="center">Hi there, I'm German Kataev 
<img src="https://github.com/blackcater/blackcater/raw/main/images/Hi.gif" height="32"/></h1>
<h3 align="center">I am a junior Data Scientist from Russia</h3>
<h3 align="center">You can see the loan approval service.</h3>
<h2 align="center">How to run the model?</h2>
<h3 align="center">Step 1. Download the "model" folder and the "main.py" file.</h3>
<h3 align="center">Step 2. Because this is localhost web app. Download and install Postman.</h3>
<h3 align="center">Step 3. Run linux or gitbash command prompt. Go to the folder with the project files and run the application with the command "uvicorn main:app --reload".</h3>
<h3 align="center">Step 4. Run Postman. Insert a JSON data file like this in the request body. Data can be taken from the database file, which is in the releases for the project.</h3>
<h3 align="left">{</h3>
<h3 align="left">    "Loan_ID": "LP001014",</h3>
<h3 align="left">    "Gender": "Male",</h3>
    <h3 align="left">    "Married": "Yes",</h3>
    <h3 align="left">    "Dependents": "3+",</h3>
    <h3 align="left">    "Education": "Graduate",</h3>
    <h3 align="left">    "Self_Employed": "No",</h3>
    <h3 align="left">    "ApplicantIncome": 3036,</h3>
    <h3 align="left">    "CoapplicantIncome": 2504,</h3>
    <h3 align="left">    "LoanAmount": 158,</h3>
    <h3 align="left">   "Loan_Amount_Term": 360,</h3>
    <h3 align="left">    "Credit_History": 0,</h3>
    <h3 align="left">    "Property_Area": "Semiurban"</h3>
<h3 align="left">}</h3>
<h3 align="center">Step 5. For prediction, select the post request type and enter the command 127.0.0.1:8000/predict.</h3>
<h3 align="center">Step 6. Get a loan decision. Output 0 or 1. Where 1 - the loan is approved.</h3>
<h3 align="center">Step 7. Invite me for an interview to make useful and effective ML models together. =) </h3>
