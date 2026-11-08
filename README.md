# SmartSurvey

SmartSurvey is a comprehensive web-based survey management platform developed using ASP.NET Core MVC and SQL Server. The system allows survey creators to build, manage, distribute, and analyze surveys while providing a seamless experience for respondents to participate and submit responses online.

---

## Project Overview

SmartSurvey was developed as a graduation project to simplify survey creation and response collection through a secure and user-friendly platform.

The system supports two types of users:

- Survey Creators
- Survey Respondents

Creators can create surveys, manage questions, generate survey links, and analyze survey responses.

Respondents can access surveys through shared links and submit their responses quickly and efficiently.

---

## Features

### Authentication & Authorization

- User Registration
- User Login
- Secure Authentication
- Role-Based Authorization
- Access Denied Handling

### Creator Features

- View Creator Dashboard
- Create Surveys
- Edit Surveys
- Delete Surveys
- Generate Survey Links
- Add Questions
- Edit Questions
- Delete Questions
- View Survey Results
- Manage Profile Information
- Change Password
- Delete Account

### Respondent Features

- View Respondent Dashboard
- Take Surveys
- Submit Survey Responses
- View Thank You Page
- Manage Profile Information
- Change Password
- Delete Account

### Other Features

- Notification System
- Responsive User Interface
- Error Handling
- Secure Data Validation

---

## System Architecture

The project follows the MVC (Model–View–Controller) architectural pattern.

```text
SmartSurvey
│
├── Controllers
├── Models
├── Views
├── Data
├── ViewModels
├── Services
├── wwwroot
├── Migrations
└── Program.cs
```

---

## Technologies Used

### Backend

- ASP.NET Core MVC
- C#
- Entity Framework Core
- LINQ

### Frontend

- HTML5
- CSS3
- Bootstrap 5
- JavaScript
- jQuery

### Database

- SQL Server

### Development Tools

- Visual Studio
- Git
- GitHub

---

## Database Setup

Update the connection string inside:

```json
appsettings.json
```

Example:

```json
{
  "ConnectionStrings": {
    "DefaultConnection": "YOUR_CONNECTION_STRING"
  }
}
```

Apply migrations:

```bash
dotnet ef database update
```

---

## Installation

### Clone Repository

```bash
git clone https://github.com/your-username/SmartSurvey.git
```

### Navigate to Project Folder

```bash
cd SmartSurvey
```

### Restore NuGet Packages

```bash
dotnet restore
```

### Update Database

```bash
dotnet ef database update
```

### Run Application

```bash
dotnet run
```

---

## User Roles

### Creator

Responsible for:

- Creating Surveys
- Managing Questions
- Viewing Results
- Generating Survey Links

### Respondent

Responsible for:

- Completing Surveys
- Submitting Responses

---

## Screenshots

Add screenshots of:

- Home Page
- Login Page
- Register Page
- Creator Dashboard
- Respondent Dashboard
- Survey Details
- Survey Results
- Survey Response Page

---

## Future Enhancements

- Survey Templates
- Survey Scheduling
- Export Results to Excel/PDF
- Advanced Analytics Dashboard
- Email Notifications
- Real-Time Statistics

---

## Team Members

Developed as a Graduation Project.

---

## License

This project was developed for educational purposes.
