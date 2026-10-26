# Gym Management System

A relational database application for managing a gym: trainees, trainers, memberships and classes. Built with **Microsoft Access** and **SQL** as a team project.

## What it does

- Registers trainees and trainers and stores their details (age, gender, height, weight, specialization, and more)
- Manages membership plans (name, duration in days, price in EGP) and trainee membership enrollment with a status
- Manages classes (name, duration, cost) and trainee class subscriptions
- Lets the user search, filter, add, update and delete records through forms
- Produces reports for trainees, trainers, memberships, trainee status and trainee classes

## Database design

The database has **8 tables**:

| Table | Purpose |
|---|---|
| Trainee | Basic trainee information |
| TraineeDetails | Extra trainee details (height, weight, and other details) |
| Trainer | Trainer information |
| Trainerspecialization | Trainer specializations |
| Memberships | Membership plans, duration and price |
| TraineeMembershipEnrollment | Which trainee has which membership, start date and status |
| Classes | Classes with name, duration and cost |
| Trainee_ClassesBridge | Bridge table for the many-to-many relation between trainees and classes |

## Main features

- **30+ SQL queries** for searching, filtering (by gender, age, social status, membership status), updating (price, duration, height and weight) and deleting records
- **20+ forms** for adding, searching, updating and deleting trainees, trainers, memberships and classes, plus home pages for navigation
- **5 reports**: Trainee, Trainer, Memberships, Trainee Status, Trainee Classes

## How to run

1. Install Microsoft Access (2007 or later).
2. Download `GymSystem.accdb` from this repository.
3. Open it and enable content (macros) when Access asks.
4. Start from the home form and use the buttons to move between forms and reports.

## Technologies

Microsoft Access, SQL

## Team and my part

Team project. My contribution: **[write here what you did, for example the forms, the queries, or the table design]**

## Screenshots

*(Add screenshots of the home form, a search form and a report in a `screenshots` folder.)*
