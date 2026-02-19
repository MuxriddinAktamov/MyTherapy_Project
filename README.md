# MyTherapy – Android Medicine Reminder Application

## Description
MyTherapy is an Android application designed to help users manage daily medicine intake
and therapy routines. The app focuses on offline-first functionality, allowing users
to store data locally on the device and receive timely reminders without requiring
a backend server or internet connection.

The application demonstrates Android frontend development skills, including UI design,
state management, local data persistence, and system-level scheduling with notifications.

---

## Tech Stack

### Frontend
- Android (Java)
- Android SDK
- XML Layouts
- ViewModel architecture
- RecyclerView
- Local notifications (AlarmManager / NotificationManager)

### Data Storage
- Local storage (SQLite / SharedPreferences)
- Offline-first data handling

---

## Features
- Add, edit, and delete medicines
- Schedule medicine intake (once, twice, or multiple times per day)
- Date and time selection using native pickers
- Medicine intake reminders via local notifications
- Dashboard view for upcoming and past medicines
- Light and dark mode support
- Fully offline functionality (no backend required)

---

## Application Flow
1. User adds a medicine with schedule and dosage
2. App stores data locally on the device
3. Notification alarms are scheduled based on selected times
4. User receives reminders to take medicine
5. Intake history is displayed in the dashboard

---

## Architecture
The application follows a simple Android architecture:

- UI Layer: Activities / Fragments with XML layouts
- Logic Layer: ViewModels handling business logic
- Data Layer: Local storage for medicines and schedules
- System Services: AlarmManager for scheduling notifications

---

## Future Improvements
- Cloud sync and backup
- Multi-device support
- Improved UI animations
- Unit tests for ViewModels

## Screenshots


<img src="screenshots/1.jpg" width="250"><img src="screenshots/2.png" width="250">

<img src="screenshots/3.jpg" width="250"><img src="screenshots/4.png" width="250">

<img src="screenshots/5.jpg" width="250"><img src="screenshots/6.png" width="250">

<img src="screenshots/7.jpg" width="250"><img src="screenshots/8.png" width="250">

<img src="screenshots/9.png" width="250"><img src="screenshots/10.png" width="250">

<img src="screenshots/11.png" width="250"><img src="screenshots/12.png" width="250">

---

## How to Run
```bash
mvn clean install
mvn spring-boot:run
