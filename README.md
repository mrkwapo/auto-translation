# Cloud Vision API   Documentation

https://cloud.google.com/vision/docs/libraries

Vision API Client Libraries
This page shows how to get started with the Cloud Client Libraries for the Cloud Vision API. Read more about the client libraries for Cloud APIs, including the older Google APIs Client Libraries, in Client Libraries Explained (https://cloud.google.com/apis/docs/client-libraries-explained).

1. Installing the client library in Node.js
 npm install --save @google-cloud/vision

2. Setting up authentication
  To run the client library, you must first set up authentication by creating a service account and setting an environment variable. Complete the following steps to set up authentication. For more information, see the GCP authentication documentation (https://cloud.google.com/docs/authentication/production).

Using the GCP Console:
 1. In the GCP Console, go to the Create service account key page.
    GO TO THE CREATE SERVICE ACCOUNT KEY PAGE(https://console.cloud.google.com/apis/credentials/serviceaccountkey?_ga=2.82261525.-2034715297.1566910502)
 2. From the Service account list, select New service account.
 3. In the Service account name field, enter a name.
 4. Don't select a value from the Role list. No role is required to access this service.
 5. Click Create. A note appears, warning that this service account has no role.
 6. Click Create without role. A JSON file that contains your key downloads to your computer.

**Provide authentication credentials to your application code by setting the environment variable GOOGLE_APPLICATION_CREDENTIALS. Replace [PATH] with the file path of the JSON file that contains your service account key, and [FILE_NAME] with the filename. This variable only applies to your current shell session, so if you open a new session, set the variable again.**

# WINDOWS:

With PowerShell:

$env:GOOGLE_APPLICATION_CREDENTIALS="[PATH]"
For example:

$env:GOOGLE_APPLICATION_CREDENTIALS="C:\Users\username\Downloads\[FILE_NAME].json"
With command prompt:

set GOOGLE_APPLICATION_CREDENTIALS=[PATH]









_____________________________________________________________________________________________________________________
Below is for writing code in R



Program using R code and available libraries can deploy this code to be run automatically  by OS.

**R** is a Statistical Software (Open Source and ru s in the background): 
Go to https://www.r-project.org/ and click the "download R" link to choose a CRAN mirror from a location closest to your location.

Download and install mirror that correspond to your operating system *(Linux, Mac, Windows)*.

**R-Studio** is a Software IDE that can run on Mac, PC or Server
Go to https://www.rstudio.com/ 

Click **"Download RStudio"**

Choose the *dowload the free version of RStudio desktop*

Choose corresponding *"Installers for Supported Platforms"*.

