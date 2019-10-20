# iot_email_notification
The Project is done using Node muc(ESP266).
Code is to be uploaded using Arduino IDE and changing necessary settings to use NodeMCU.
The following code can be integrated with any other primary code and convey various messages as per need.
IOT based e-mail notification system
SMTP Server: smtp.pepipost.com
SMTP PORT: 587
You need to encode your SMTP Username and SMTP Password to Base64 format with ASCII Character Set. 
For this, you can either use an Arduino Library or a website called BASE64ENCODE.
BASE64ENCODE (link)=https://www.base64encode.org
Use client.println("Any message to be conveyed") to send the text of the email.
NOTE : smtp2go servers not working so use the above which I have adopted.
