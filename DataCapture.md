# Thinking about data capture

## What do we mean by data capture?
Data capture is simply the process of bringing data into a system. If we have a form that people have to fill in to register, and we bring that data into a database for use later, that's data capture. Data capture lies at the heart of the whole data environment; if we don't capture data, we don't have data!

## Why we need to think about data capture
![garbage in, garbage out](img/gigo.png)

Data capture is generally the moment that data quality is established. That means that if we don't focus on making sure the data we collect is of good quality, we'll have bad quality data to work with later, which is a huge headache. By good quality, we mean easy to work with, easy for programs to understand, easy to aggreagate and run calcualtions on, etc...

At the point of data capture, we need to ensure we've thought ahead to how we'll be working with that data in the future. If we're recording a phone number, we should make sure the user can't enter text. If we're recording a date of birth, we need to make sure the date is in a consistent format. Data validation and input controls on forms help ensure this; validation allows us to refuse data that isn't right for us (like when someone enters text in their phone number) and controls help ensure data is entered consistently (like requiring a users to use a date picker for their date of birth.)

## What do our regulators say about collection?
Yup, we're back to GDPR again! GDPR establishes rules for how we collect and handle data, to make sure we do so in the best interest of data subjects:

![gdpr](img/gdprcollection.jpg)

... Providing yet more considerations when establishing a system of data capture.

## Principles
Here are some key principles that will make it easier to think about data capture:

### Keep It Simple Stupid
Create forms and inputs that are easy to understand, and leave no ambiguities about what is required. Make it as simple as possible for people to fill in; don't call that field number, call it mobile number!

### Be conventional
Conventions exist for a reason; they make it easier for people to do things quickly. It's conventional for a registration form to start with the name details, so start with the name details. Sturcture your forms in a way people expect, and you'll get better data (not mention more completed forms!)

### Be consistent
Nothing trips a user up quite like inconsistencies. If you ask for mobile number with a country code, and home number without, that's going to cause users to pause or become confused. It leads to poorly completed forms (see above) and it also leads to bad data, as it's harder to compare values across fields.

### Minimise actions
The more a user has to do, they less likely they are to do it. If you don't need to record why they chose to fill out this form on a Monday, and what the weather is like outside, then don't! If a user can quickly tab and click their way through a short and elegent form then they're more likely to complete it, and more likely to comeplete it accuartely.

### Think about diversity
OK, so maybe it's not going to factor into data quality; but do you really need to record a user's title? If there are ways that you can be more inclusive, like skipping title or gender, or including a more full list of genders (rather than just male or female) then your users are going to be happier. If nothing else, a happy user is more likely to take the time to make sure they've filled out the form accurately.

### Assist folks in filling the form out well
In the scope of filling out webforms, little is more annoying that clicking subm it, only to see big red text telling you you did something wrong. Oh, *now* you tell me that my password has to be less than 16 characters! This is easily avoided by telling the user what they need to do upfront; provide tooltips in form fields, hover text or call outs. Make it as easy as possible to give you the data you want, in the format you need.

## Planning data capture
Great, so what now? Time to plan out your data capture!

## What information do you need to perform the associated task?


## What types of analysis are you expecting to do?


## Do you **REALLY** need that personally identifiable info?


## What data types do I need and which fields can come from a constrained list?


## What things can I do to make it easier to for folks to complete the form?


## What audit data do I need?


## Demo
Lets take a look at a quick demo now, in which we use the super handy webforms service, Airtable, to design a form for managing a bacon roll run!

## Exercises
1. Identify a form that you use regularly
2. What parts make it easier for you to fill in?
3. Which parts make it harder for you to complete?
4. What ways could this form be amended?

## Recommended resources amd readings
- :book: [Nudge](http://geni.us/nudge)
- :page_facing_up: [Design better forms](https://uxdesign.cc/design-better-forms-96fadca0f49c)
