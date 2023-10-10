# HackAI_230600
Project name: Temperature Alert Agent

Description:
This project is a temperature alert agent that uses the uAgent library to connect to a free weather API to fetch real-time temperatures for a specified location. It also allows users to set their preferred temperature range and location, and sends an alert/notification to the user when the current temperature in their chosen location goes below the minimum or above the maximum threshold they've set.

Instructions to run the project:

i.Install the required dependencies:
  pip install uagent
ii.Create a .env file with the following placeholders for your API keys:
   OPENWEATHERMAP_API_KEY=YOUR_OPENWEATHERMAP_API_KEY
iii.Get your API keys from the following websites:
    OpenWeatherMap: https://openweathermap.org/api
Fill in the placeholders in the .env file with your API keys.

Run the following command to start the Temperature Alert Agent:

python main.py
Special considerations:
If you are using a cloud-based platform to host your project, you may need to configure environment variables to store your API keys.
You can customize the alert method used by the Temperature Alert Agent by modifying the send_alert() function.
