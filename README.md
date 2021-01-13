#Twilio API Messenger

With a free Twilio account, you only get to text verified numbers.

The program uses Twilio API to sendtext message to your registered mobile number.

1. Create a Github account.
2. Create an account on Twilio.
3. Verify a Phone Number on Twilio https://www.twilio.com/console/phone-numbers/verified. That you would like to text.
4. Get Twilio Credentials
 https://www.twilio.com/console
 Get Account SID
 Get Auth Token
5. Get Phone Numbers
 Your Twilio Number is Here
 Verified Cell Phone Number You Want To Text

6. In credentials.py, update the account_sid, auth_token, twilio_num with values from your Twilio account and update mobile_num with with a mobile phone number. The phone numbers must be in the following format:
    [+][country code][phone number including area code]

7. Install requirements.
    pip install -r reqirements.txt
    
#Congratulations!
 You just sent your first text through your Python Text App that uses the Twilio API.
