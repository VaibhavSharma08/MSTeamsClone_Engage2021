# MSTeamsClone_Engage2021
This repository contains the source code for the Clone of MS Teams as required for the submission of ENGAGE 2021. 
The website is currently live at "http://35.80.201.240:3000/"

# How to Run
# a) Running the Live Website Demo
The code demo currently works in Google Chrome after going through some specific steps. These are given as follows:
**Step 1**: Open Google Chrome and enter "chrome://flags/" in the URL. 

**Step 2**: Enter the term "Insecure origins treated as secure" in the search bar. In this section enter the URL -> "http://35.80.201.240:3000" and Enable the Flag.

![image](https://user-images.githubusercontent.com/62774848/125496222-e211bfcc-1f84-4ffb-9f71-9b1be67712c0.png)

**Step 3**: Restart Chrome according to the prompt.

**Step 4**: Visit the URL "http://35.80.201.240:3000/" and enter the room you want to connect to. 

**Step 5**: Allow the browser to use your camera and microphone. Then use another device or open another tab and navigate to the same URL and enter the same room.

Voila! You can now chat with the other person from your browser.

**Reason for doing this:** The getUserMedia function only works over HTTPS. Since the website is currently available over HTTP only, we need to explicitly enable data transmission over HTTP. Hence the extra steps.


# b) Running the Local Host Demo
The code demo has been tested to work in Google Chrome and Mozilla Firefox. The steps are given as follows:

**Step 1**: Download the source code and extract the files from the ZIP file.

**Step 2**: Open the command prompt and navigate to the source code directory. 

**Step 3**: Run the command "node server.js". 

![image](https://user-images.githubusercontent.com/62774848/125500788-2bc19499-24f6-4c46-a7c7-a90b9ffce0d2.png)

**Step 4**: Navigate to "localhost:3000/". Enter the room you want to connect to. Allow the browser to use your camera and microphone. Then open another tab and navigate to the same URL and enter the same room.

![image](https://user-images.githubusercontent.com/62774848/125501205-b1b171a1-4518-4d10-8972-992db3e2da95.png)

Voila! You can now chat with yourself from your browser :)




# Submission Details:
Name - Vaibhav Sharmaa

College - Netaji Subhas University of Technology

Contact Number - 9873994422

Email - vaibhavs755@gmail.com
