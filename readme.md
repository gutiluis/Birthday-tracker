Birthday App
---
loads data from `birthdays.csv`, and users get presented with a menu.

Users can:
- See upcoming Birthdays, which are birthdays within the next 90 days
- Check someone's age by entering their ID as prompted
- Compare two people's ages by entering their IDs as prompted
- Quit the app

### TO DO
- Create a helper function that determines the age, which both `display_age()` and `upcoming_birthdays()` can use.
- Create a helper function that takes the date string and returns a datetime object (all 3 functions can use this!)
- List the upcoming birthdays chronologically
- Try to handle plural cases! Create a function in `utils.py` that will determine whether we print plural words or singular words. For example, "0 months", "1 month", "2 months".
- Handle upcoming birthdays for the following year
---
-python3 -m venv venv
-source venv/bin/activate
-pip install dateutil
