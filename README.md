Cara menjalankan program :

Click Fork in the right corner of the screen to save it to your Github.

Visit https://dashboard.ngrok.com to get NGROK_AUTH_TOKEN

In Github go to Settings> Secrets> New repository secret

In Name: enter NGROK_AUTH_TOKEN

In Value: visit https://dashboard.ngrok.com/auth/your-authtoken Copy and Paste Your Authtoken into

Press Add secret

Go to Action> AWS-RDP> Run workflow

Reload the page and press AWS-RDP> build

Press the down arrow on Connect To Your RPD to get IP, User, Password.

IF MY REPO GOT DELETED,ON YOUR GITHUB GO TO .github/workflows > main.yml AND EDIT NEW LINK TO YOUR REPO. Include ALL Prerequisite in Files FOLDER
