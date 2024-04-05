<h1 align = "center" >Medication Label Scanner</h1>
<div align = "center" ><img height = "200px" src = "https://github.com/abGit9/Med_Label_Reader/assets/50727486/649ee9ab-6286-4600-9a4d-8ca57e9c7ea5"></img></div>
<br>
<div align = "center"><a href="https://www.flaticon.com/free-icons/ocr" title="ocr icons">Ocr icons created by Freepik - Flaticon</a></div>
<br>

<p>Welcome to the GitHub repository for the Medication Label Scanner! This web service was developed to streamline the process of entering medication information into the <a href="https://github.com/abGit9/Pilly_Intro">Pilly</a> App, making it more efficient and user-friendly.</p>


<h2>Overview</h2>
<p>The Pilly App faces a common issue amongst its users: manual data entry is too long and time-consuming. To address this, we created a web service that automates this process. Users simply take a photo of their medication label and upload it. The service then interprets the label, identifies the medication, and returns the relevant data to the user.</p>
<p>This application is developed in Python and is hosted on Google Cloud App Engine. It leverages the power of the Google Vision API to recognize text within images. The text is then matched against a database of medication names, compiled using the DailyMed (NLM) API. Our service currently achieves a 65% accuracy rate in interpreting medication labels and is continuously being improved.</p>

<h2>Languages</h2>
<ul>
    <li><b>Python</b></li>    
</ul>
<h2>Features</h2>
<ul>
    <li><b>Automated Medication Entry: </b>users can upload a photo of their medication label via an HTTP POST request. The service processes the image and returns organized medication information.</li>    
</ul>

<h2>Platform</h2>
<ul>
    <li><b>Google Cloud App Engine: </b>chosen for its cost efficiency and self-maintaining infrastructure, Google Cloud App Engine allocates resources on demand and manages the infrastructure, allowing us to focus on improving the application.</li>    
</ul>

<h2>Technologies Used</h2>
<ul>
    <li><b>Flask Web Framework:</b> chosen for its simplicity and ability to abstract basic web operations. It is used explicitly in routing HTTP requests via the route decorator.</li>    
   <li><b>Google Vision API:</b> used to extract text from images of medication labels. Accessing the API required authenticating our application and authorizing its function.</li>   
   <li><b>DailyMed (NLM) API:</b> utilized to create a SQL database of medication label data. This database is then queried to match against the text output from the Vision API, enabling the identification of medications.</li>   
</ul>
<h2>Website</h2>
<p>Visit our website to see a demonstration and gain insights into the implementation.
<a href="https://abhat.io/app/software/cloud/cloud.html">Medication Label Reader</a>
</p>
<h2>Closing</h2>
<p>By automating the entry of medication information, we aim not only to enhance the user experience but also to contribute to more efficient healthcare practices. We are committed to continuous improvement and deeply value the feedback and contributions of our users and developers.</p>
<p>Thank you for your interest and support. Together, we can make a meaningful impact.</p>


