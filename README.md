# SummerAssignment
Using a .csv file to create methods to analyze the data in the file. 

**Source of the data:** I used my friend Kate's screentime log off of her iPhone, 
after gaining her permission to do so. I am allowed to use this data as she
gave me verbal permission.

**What does each row represent?** Each row/entry represents a day that Kate used
her phone. For example, one of the entries is July 1st, which is a day that 
Kate used her phpne.

**What if you needed to design a class?** I would need the following fields for each
object: date, total screen time, time of first use, screen on battery usage, most used app, 
pickups, and notifications. Therefore, I would need 7 fields for each object.

<img width="360" height="500" alt="Screenshot 2025-09-14 at 7 04 01 PM" src="https://github.com/user-attachments/assets/11c14965-0ff1-441c-b511-c0075129c351" />

**Bullet Points**
- Date: The date represents the day Kate used her phone. The date is recorded as a double, with any numbers on the left side of the decimal point representing the numerical month (7 = July) and any numbers on the right side of the decimal point representing the number day in the month. For example, 7.1 represents July 1st.
- Total Screen Time (Minutes): This represents the total amount of minutes Kate was on her phone
- Time of First Use (Time): This represents the first time Kate used her phone. It is set on a 24hour clock, so 0.00 means she first used her phone at 12:00 AM.
- Screen On Battery Usage (Minutes): This represents the amount of time the screen has been on while running on battery power. This means that it doesn't represent any time that you were using your phone while it was charging or plugged in.
- Most Used App: This column shows which app was the most used depending on screen time. In other words, it shows which app had the most screen time
- Pickups: Represents the number of times Kate picked up her phone that day
- Notifications: Represents how many notifications/alerts Kate recieved on her phone each day. These are notifications that pass through the "Do Not Disturb" feature that was enabled, so it may not be a true indicator of the amount of notifications she recieved.

