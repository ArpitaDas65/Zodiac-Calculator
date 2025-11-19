# Zodiac-Calculator

🌟 Zodiac Sign Calculator

A simple and interactive web app that allows users to enter their name, birth date, and get:

✔ Their Zodiac sign

✔ A random compliment

✔ A comforting victim-support message

✔ A personalized recommendation


This tool blends astrology with positivity and motivation to create a unique experience.




✨ Features

🔮 Accurate Zodiac Sign Detection

Based on standard Western astrology date ranges.

💬 Personalized Messages

The app generates:

A compliment

A healing message (for emotional support)

A helpful recommendation


Each message is selected using a custom index formula based on the user’s name, date of birth, and surname.

🎨 Simple & Clean UI

Just fill out the form and hit Calculate — your result appears immediately.




📦 Project Structure

├── index.html      # Main webpage
├── style.css       # Styling for the UI
├── ind.js          # Core JavaScript logic
└── README.md       # Project documentation




🛠️ How It Works

1. User enters:

Name

Surname

Birth Day

Birth Month

Birth Year



2. JavaScript validates the date.


3. The Zodiac sign is determined using getZodiacSign().


4. A compliment, victim-support message, and recommendation are chosen using formulas:

Based on name length

Birth day

Birth month

Birth year



5. A personalized message is displayed on the page.





🧠 Key Functions

getZodiacSign(day, month)

Returns the Zodiac sign for the given date.

getIndex(value, max)

Returns a safe array index using modulo.

generateMessage()

Main function that:

Validates inputs

Gets zodiac sign

Gets indexes

Displays the full personalized message



🚀 How to Use

1. Open index.html in any browser.


2. Fill in your:

Name

Surname

Day

Month

Year



3. Click Calculate (make sure button calls generateMessage())


4. Your zodiac and messages will appear instantly.




💡 Future Improvements (Optional)

Save previous results

Add more message categories

Add horoscope predictions

Add animations and modern UI

Convert to React/Flutter version
