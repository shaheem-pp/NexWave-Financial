# NexWave-Financial

------

NexWave Financial is a made-up bank-like place that makes special cards for students from other countries. This project is about making an app for phones that helps with money stuff like sending money, checking balance, and looking at past transactions. The app is made for people who are just starting to learn how to make apps.

## What It Does

- **Log In**: People can sign in with their email. The app keeps them logged in safely using something called JSON Web Tokens (JWT).

- **Manage Money**: People can do money things like sending money, checking their past money stuff, and seeing how much money they have.

- **Send and Get Money**: People can send money to others and get money from them using the app.

- **Keep Safe**: The app uses a PIN or Face ID to make sure only the right person can get into it and see their money stuff.

## What We Used

- **Django Rest Framework**: This helped us make the part of the app that talks to the internet and saves your money information.

- **PostgreSQL**: This is like a very safe box where we keep all the money information so no one can get it without permission.

- **SwiftUI**: This helped make the app look good and work well on iPhones.

## How to Start

1. **Get the Code**: Copy the code from this place: `git clone https://github.com/shaheem-pp/NexWave-Financial.git`

2. **Set Up the Internet Part**:
   - Go into the `backend` folder.
   - Make sure you have all the stuff the app needs by typing: `pip install -r requirements.txt`
   - Make everything ready: `python manage.py migrate`
   - Start the internet part: `python manage.py runserver`

3. **Set Up the iPhone Part**:
   - Open the Xcode project in the `ios` folder.
   - Make sure everything for SwiftUI is set up right.
   - Make the app work on your phone or a pretend phone.

4. **Start Using the App**: Sign in with your email, do money things, and see what NexWave Financial can do.

## Help Us Make It Better

We're happy if you want to help! If you have any ideas to make it better or find any problems, tell us by opening an issue or suggesting a change.

## Thanks

- Thanks to Django Rest Framework and SwiftUI for helping us make this app.
- We thought of this idea because we saw that students from other countries sometimes need special money services.

## NOTE

- This is just for learning, not for cheating in school or anything like that.
