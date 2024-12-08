# quicksms

Quick SMS
Quick SMS is a user-friendly Django web application that enables fast and personalized SMS communication. Powered by the reliable Twilio API, it’s ideal for staying connected with friends, family, or clients in just a few clicks.

Features
Effortless SMS Sending: Compose and send messages to any valid phone number quickly.
Personalized Greetings: Choose from predefined greetings to add a thoughtful touch to your messages.
Streamlined Interface: Clean, intuitive design with clear instructions for an easy user experience.
Real-Time Feedback: Get instant success confirmations or helpful error prompts for troubleshooting.
Twilio Integration: Leveraging Twilio ensures reliable global message delivery.

How It Works
Home Page Introduction
Start at http://127.0.0.1:8000/.
A welcoming overview of Quick SMS and its features is displayed.
Click the "Send a Message" button to proceed to the SMS form.
Send SMS Page
On this page, users can craft their personalized SMS messages with a simple form:
Select a Greeting: Choose a tone for your message from a dropdown menu.
Enter Recipient Details: Provide the recipient's full name for personalization.
Compose the Message: Write the SMS content in the provided text box.
Input Phone Number: Enter the recipient's phone number in international format (e.g., +639123456789).
Once the form is complete, click "Send SMS" to send the message.

Feedback
Success Notification:
A confirmation appears after successful delivery, with an option to send another message.
Error Handling:
In case of failure, an error prompt identifies the issue and suggests corrective actions.

How to Execute / Run
Start the Server:
Run the Django development server using:

python manage.py runserver  
Open the Application:
Navigate to http://127.0.0.1:8000/ in your web browser.
Send SMS:
Follow the How it Works section instructions to compose and send SMS messages.

Tech Stack
Backend Framework: Django 5.1.3
Programming Language: Python 3.12.1
Twilio API: For sending SMS messages
Frontend: HTML, CSS (Bootstrap for UI styling)



Quick SMS makes SMS communication simple yet impactful, ensuring each message is delivered with care and precision for both personal and business purposes.
