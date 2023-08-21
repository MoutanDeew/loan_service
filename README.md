<h1 align="center">You can see the loan approval service.</h1>
<h2 align="center">Project goals:</h2>
<h3 align="left">1) Create a local loan approval service. (Indicative value ROC-AUC ~ 0.65)</h3>
<h3 align="left">2) The model will take a json file with a client profile as input and give an output of 0/1 (1 - if the loan is approved).</h3>

<h2 align="center">How will the project help the business?</h2>
<h3 align="left">This model is sure to be cost-effective in the lending market. Reduce loan decision time after a few days, as was done in the past with the help of the loan managers department, to a few minutes. The project will help increase the company's income and conversion.</h3>

<h2 align="center">What is to be done?</h2>
<h3 align="left">Solve the separation difference.</h3>

<h2 align="center">How to run the model?</h2>
<h3 align="left">Step 1. Download the "model" folder and the "main.py" file.</h3>
<h3 align="left">Step 2. Because this is localhost web app. Download and install Postman.</h3>
<h3 align="left">Step 3. Run linux or gitbash command prompt. Go to the folder with the project files and run the application with the command "uvicorn main:app --reload".</h3>
<h3 align="left">Step 4. Run Postman. Insert a JSON data file like this in the request body. Data can be taken from the database file, which is in the releases for the project.</h3>
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
<h3 align="left">Step 5. For prediction, select the post request type and enter the command 127.0.0.1:8000/predict.</h3>
<h3 align="left">Step 6. Get a loan decision. Output 0 or 1. Where 1 - the loan is approved.</h3>
<h3 align="left">Step 7. Invite me for an interview to make useful and effective ML models together.</h3>
<h3 align="center"><img src="https://media.giphy.com/media/UqZ4imFIoljlr5O2sM/giphy.gif" width="300"/></h3>
