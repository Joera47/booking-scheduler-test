# Booking Scheduler Test
A simple front-end test involving user profiles & timeslots

## Getting started
Your task is to create a booking scheduler system which executes this [user flow](https://raw.githubusercontent.com/Joera47/booking-scheduler-test/master/User%20Flow.png).

### User flow examples
Here are example screenshots which follows the user flow from above,

1. [User Index](https://raw.githubusercontent.com/Joera47/booking-scheduler-test/master/flows/User%20Index.png)
2. [User Show (Optional)](https://raw.githubusercontent.com/Joera47/booking-scheduler-test/master/flows/User%20Show.png)
3. [Booking Form](https://raw.githubusercontent.com/Joera47/booking-scheduler-test/master/flows/Booking%20Form.png)
4. [Booking Form 2](https://raw.githubusercontent.com/Joera47/booking-scheduler-test/master/flows/Booking%20Form%202.png)
5. [Booking Success](https://raw.githubusercontent.com/Joera47/booking-scheduler-test/master/flows/Booking%20Success.png)

### User Profiles
You are given example character profiles, which can be found [here](https://github.com/Joera47/booking-scheduler-test/blob/master/character_profiles).

You are allowed to copy the profiles into your code, and add details to the array/hash if it helps in your methods or iterations.
However, core details such as the **name, profession, photo & availability** should be left unchanged.

### User Availability
The mentor's availability is listed in the has as **"availability"**.
Availabilities are listed as **"day/hour"**.
For example: **"0/13:00"**, **0 (Monday)** refers to the day, and **13:00 (1PM)** refers to the hour.

Days are listed according to this hash map.

{
  "0" => "Monday",
  "1" => "Tuesday",
  "2" => "Wednesday",
  "3" => "Thursday",
  "4" => "Friday",
  "5" => "Saturday",
  "6" => "Sunday"
}

These timeslots are repeated every week. Meaning that the mentor will be **available** at the same time and day every week.
In your assessment, you are only required to list out their availability up to the next 30 days.

## Your Task
- You will need to create a mock mobile app based on the given user flows.
- Having a database is not necessary and it is not necessary to save the bookings created. This is just a mock, and what is important is that information selected or submitted in the previous page carries over to the next.
- Should have efficient logic, as in it should not be hard-coded.
- Have visually acceptable/pleasing styling.
- You will need to present your mobile app mock at the end of the presentation, on projector. You are to explain your design considerations, and how the app works.

### Optional
- **User Show** page is optional, but would improve the flow significantly.
- **Additional animations** would improve the UI and create a better experience.
- **Database** to save user profiles or bookings created are not necessary, but you may include it if it helps with your implementation.
