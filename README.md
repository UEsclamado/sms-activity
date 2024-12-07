# quicksms

Quick SMS - Django SMS Sending Application

Quick SMS is a user-friendly Django web application that lets you send personalized SMS messages quickly and easily. Powered by the reliable Twilio API, it’s perfect for fast and meaningful communication with friends, family, or clients.

Features

Effortless SMS Sending: Compose and send messages to any valid phone number in just a few clicks.
Personalized Greetings: Select from predefined greeting options to add a personal touch to your messages.
Streamlined Interface: Clean, user-friendly design with clear instructions ensures an easy messaging experience.
Real-Time Feedback: Instant confirmation for successful messages or helpful error prompts for troubleshooting.
Fully Integrated with Twilio: Ensures reliable message delivery to recipients worldwide.

How It Works

Home Page
Introduction: Start at http://127.0.0.1:8000/, where you’re greeted with a concise explanation of Quick SMS and its capabilities.
Navigate to the Form: Click the "Send a Message" button to proceed to the SMS form.

Send SMS Page
On the Send SMS page, users are provided with a straightforward form to craft their message:

Select a Greeting: Choose a greeting from a dropdown menu to set the tone of your message.
Enter Recipient Details: Provide the recipient’s full name for personalization.
Compose the Message: Write the body of your message in the text box provided.
Input Phone Number: Enter the recipient's phone number in international format (e.g., +639123456789).
Once completed, hit the "Send SMS" button to dispatch the message.

Feedback
Success Notification: A confirmation message appears when the SMS is sent successfully, along with an option to send another message.
Error Handling: If the message fails, an error prompt guides you to correct the issue and try again.

Quick SMS takes the hassle out of SMS communication. By combining simplicity with functionality, it ensures that every message is delivered with care and precision. Whether you're reaching out for business or personal reasons, Quick SMS makes your communication impactful.

Usage

Open the application at http://127.0.0.1:8000/.
Click "Send a Message" on the homepage.
Fill out the SMS form with the required details:
Select a greeting.
Enter the recipient's name.
Compose your message.
Provide a valid phone number.
Click "Send SMS" to send the message.
View the confirmation or error message and take further action as needed.

How to Execute / Run

Start the Server: Run the Django server using:
python manage.py runserver  
Open the Application: Navigate to http://127.0.0.1:8000/ in your browser.
Send Messages: Follow the instructions in the "Usage" section to send SMS messages.
