|          |                            |
|----------|----------------------------|
| filename | appointment-booking.html   |
| title    | Make an Appointment        |
-----------------------------------------

This page is intended to allow our patients to book an appointment quickly and intuitively, without the need for contacting us directly. We have already engaged a different contractor to work on handling the appointments that are received, but we will still need you to design the form. All in all, we prefer the usage of AskMyGP for making appointments, and as such, we would like you to include the following passage before the formula:

> If you'd like to make an appointment, please consider the usage of AskMyGP, a free app that allows you to book appointments easily and contact Dr. Olivier from the comfort of your own home by video. Booking an appointment through the app will make it easier for us to process your appointment. If however you are unable to use AskMyGP for whatever reason, you may also use the form below:

Our AskMyGP link and a possible image / box to click for transfer has been given in the [contact.md](contact.md) page description.

In case a patient decides to use the form, they have to identify themselves to book an appointment. For this, they should enter their name, birth date and policy number (of course, this appointment booker only works if they are already registered with us as a patient). They should also be able to state a reason for the appointment, such as "I'm feeling sick", "Routine Checkup" or "I want to be vaccinated". In the latter case, it should also be possible to choose the type of vaccination (e.g. the Flu, or the new Corona vaccination once it becomes widely available). The average length of the appointment depends on the reason of the visit. 

Once all information is put in, a list of possible appointments (date and time) should pop up for the user to choose from. Our contractor says that this information will be sent as an "XML file". **## TODO: XML File ##**

After an appointment is chosen, the user should see a confirmation of the booking and be lead back to our home page.


**Note:** You do not need to give actual functionality to these pages yet. All our contractor wants is the design. So the "Submit" buttons should simply lead to the appointment list based on the example XML and the confirmation window.

Reasons for the appointment:
- House visit
- Psychosomatic care
- Nutritional advice
- Vaccination advice
- Vaccination
- General Health Examination
- Cancer screening examination
- Other => Results in extra field

=> Textarea to provide as much information as possible
