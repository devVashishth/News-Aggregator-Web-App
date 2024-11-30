# News-Aggregator-Web-App
Android Developer Nanodegree Capstone Project.
A bit overview, it uses newsapi.org API to get news and get JSON data back. Then it is parsed using google's gson library and the requests are sent by Retrofit.

Note: To run the app you have to add NewsAPI.org key. I have taken this step to due to limited access to daily request for News. Getting a key would take just few seconds :)
Run the app

Clone the app with .git url
Open /home/.gradle/gradle.properties and add the following line (Create the file if not exists)
NewsApi_ApiKey=<YOUR API KEY>
Run the app by Shift + F10 or clicking Run
Setup API Key
Visit NewsAPI.org to get your API Key
Copy your API Key from accounts section
Open gradle.properties (Create the file if not exists)
For Linux/Mac: /home/.gradle/gradle.properties
For Windows: C:\Users\<UserName>\.gradle\gradle.properties
Add the following line:
NewsApi_ApiKey="YOUR_API_KEY"
