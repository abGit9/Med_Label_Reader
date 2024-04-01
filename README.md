<div align = "center" ><img height = "200px" src = "https://github.com/abGit9/Med_Label_Reader/assets/50727486/649ee9ab-6286-4600-9a4d-8ca57e9c7ea5"></img></div>
<br>
<div align = "center"><a href="https://www.flaticon.com/free-icons/ocr" title="ocr icons">Ocr icons created by Freepik - Flaticon</a></div>
<br>
<h1 align = "center" >Medication Label Scanner</h1>
<p>Welcome to the GitHub repository of the Pilly App's Medication Label Scanner Service! This innovative web service was developed to streamline the process of entering medication information into the Pilly App, making it significantly more efficient and user-friendly.</p>


<h2>Overview</h2>
<p>The Pilly App faced a common challenge among its users: the time-consuming task of manually entering medication information. To address this issue, we created a web service that automates this process. Users can simply take a photo of their medication label and upload it. The service then interprets the label, identifies the medication, and returns the relevant data to the user.</p>
<p>This application is developed in Python and is hosted on Google Cloud App Engine. It leverages the power of the Google Vision API to recognize text within images. The text is then matched against a database of medication names, compiled using the DailyMed (NLM) API. Our service currently achieves a 65% accuracy rate in interpreting medication labels and is continuously being improved.</p>


<h2>Features</h2>
<ul>
    <li><b>Automated Medication Entry: </b>Users can upload a photo of their medication label via an HTTP POST request. The service processes the image and returns organized medication information.</li>    
</ul>

<h2>Platform</h2>
<ul>
    <li><b>Hosted on Google Cloud App Engine: </b>Chosen for its cost efficiency and self-maintaining infrastructure, Google Cloud App Engine allocates resources on demand and manages the infrastructure, allowing us to focus on improving the application.</li>    
</ul>

<h2>Technologies Used</h2>
<ul>
    <li><b>Flask Web Framework:</b>We chose the Flask web microframework for its simplicity and ability to abstract basic web operations. It is used explicitly in routing HTTP requests via the route decorator.</li>    
   <li><b>Google Vision API:</b>This API is used to extract text from images of medication labels. Accessing the API required authenticating our application and authorizing its function.</li>   
   <li><b>DailyMed (NLM) API:</b>We utilize this API to create a SQL database of medication label data. This database is then queried to match against the text output from the Vision API, enabling the identification of medications.</li>   
</ul>
<br>


