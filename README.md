# Welcome To Poiótēs Flask Back-End
This aim's to improve Image quality for web development in different screen size

## Get Started

Initiate Virtual Environment with command:
- python3 -m venv venv

Start Envirnoment with command:
- source venv/bin/activate

Deactivate Environment with command:
- deactivate

Install packages in requirements.txt with command:
- pip3 install -r requirements.txt

create .env file and extract from environment variable from .env.simple
- cp .env.simple .env

Generate secret key in .env
- chmod +x secret_key_gen.py
- ./secret_key_gen.py

Start environment with command:
- python3 app.py 


# Contents of Boilerplate

The boilerplates should contain the following

- A proper structure of the project according to the norms of the framework
- Authentication (including social authentication) + magic link authentication + in-app authentication screens (e.g change password)
- Messaging (email), including default templates and using background processes
- Payments (Stripe, Flutterwave integration, LemonSqueezy), internal and external
- Users
- Manage Users
- Superadmin interface (users, orgs, payments, activity log)
- Settings page
- Profile Settings
- Landing page (various, e.g privacy policy, about us)
- Contact Us
- GPDR cookies
- Basic Dashboard
- Waitlist (coming sooon)
- Squeeze / Marketing Page
- Invite flow
- User data export
- Random Data associated to user + List of Random Data on the Dashboard - e.g Widgets in System.
- View of Single Data - e.g a single Widget associated with a user
- Other Data List with Search + Sorting
- Chart page with chart of data
- Content Edit Page
- Notifications
- Invite Link
- Language and Region
- Email Template Management in the Superadmin (html)

## No UI
- Database
- Documentation on how to use each feature deeply
- AI Integration
- Migrations
- Recommendations
- Activity Log
- Push Notifications
  
# Notes
boilerplate must contain instructions on how to keep your code as decoupled as possible, so it is easy to remove things not needed. boilerplate must contain the standards used in coding. boilerplate must contain a license file.

# How to contribute code


# References
(1) https://www.codecademy.com/resources/docs/contribution-guide
