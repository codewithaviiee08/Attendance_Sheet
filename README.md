# 📊 Attendance & Payroll Management System 2027

A professional, responsive **Attendance & Payroll Management System** built using **HTML, CSS, and JavaScript**. Manage daily attendance, working hours, leaves, holidays, salary estimates, and monthly reports from one dashboard.

## ✨ Features

- 🔐 **Admin Login** — demo login screen
- 📅 **Full-Year Calendar** — January 2 to December 31, 2027, including Sundays
- 🕒 **Daily Attendance** — record IN time, OUT time, status, project, and remarks
- 📈 **Automatic Work Hours** — calculate working hours from IN/OUT times
- 🏖️ **Leave Management** — present, absent, paid leave, and unpaid leave
- 🎉 **Holiday Management** — add company holidays and festivals
- 💰 **Salary Estimation** — monthly gross, deductions, and estimated net salary
- 📊 **Dashboard Analytics** — attendance totals and payroll snapshots
- 🗓️ **Monthly Reports** — review attendance and salary estimates month by month
- 📤 **CSV Export** — export attendance records for spreadsheets
- 💾 **JSON Backup** — download a backup of saved data
- 🎨 **Theme Customization** — light/dark themes and accent colors
- ⚙️ **Configurable Settings** — salary, weekly off, standard hours, and deductions
- 💻 **Browser-Based Storage** — saves settings and attendance in local browser storage

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Application structure |
| CSS3 | Responsive styling and themes |
| JavaScript | Attendance logic and calculations |
| LocalStorage | Saving data in the browser |
| CSV / JSON | Export and backup |

## 📂 Project Structure

```text
attendance-payroll-2027/
│
├── index.html   # Main application and login page
├── style.css    # UI styles and responsive design
├── script.js    # Attendance and payroll logic
└── README.md    # Project documentation
```

> If your current project uses a single `index.html` file containing its CSS and JavaScript internally, you can keep that structure or split the code into separate files.

## 🚀 Getting Started

### 1. Download or Clone the Project

If you have uploaded the project to GitHub, clone it with:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Or download the repository as a ZIP file and extract it.

### 2. Open the Project

1. Open the project folder.
2. Locate `index.html`.
3. Double-click the file to open it in your browser.

No Node.js installation or database setup is required for this browser-based version.

### 3. Demo Login

Use these demo credentials to access the dashboard:

| Field | Demo value |
|---|---|
| User ID | `ADMIN@26` |
| Password | `Abhi@26` |

**Security note:** These credentials are hardcoded in the front-end JavaScript. This is a demo login, not secure authentication for confidential employee or payroll records.

## 📋 How to Use

1. **Sign in:** Enter the demo credentials.
2. **Overview:** Review attendance totals and salary estimates.
3. **Daily Attendance:** Select a month and enter IN/OUT times.
4. **Choose Status:** Mark present, absent, paid leave, unpaid leave, holiday, or weekly off as appropriate.
5. **Settings:** Configure salary, work hours, weekly off, deduction percentage, and theme.
6. **Holidays:** Add company-approved festivals and public holidays.
7. **Monthly Summary:** Review attendance and estimated payroll for each month.
8. **Export & Backup:** Download CSV reports or a JSON data backup.

## 💵 Payroll Calculation

The application estimates salary using the configured monthly salary and calendar-day method.

- **Estimated gross salary:** Monthly salary minus applicable unpaid absences and unpaid holidays.
- **Estimated deduction:** Gross estimate multiplied by the configured deduction percentage.
- **Estimated net salary:** Gross estimate minus the configured deduction.

These are estimates based on the application's settings. Actual payroll, TDS, statutory deductions, overtime, and leave policies may differ. Verify the rules applicable to your employer before relying on the figures.

## 💾 Data Storage

Attendance entries, holidays, and settings are saved in the browser's `localStorage`.

- Data is specific to the browser and device.
- Clearing browser data may erase saved records.
- CSV export and JSON backup are available.
- Data does not automatically synchronize between devices.

## 🔒 Security & Limitations

This project is intended as a **learning project or local demo**.

- Login validation runs in the browser and can be bypassed.
- LocalStorage is not a secure database.
- There is no server-side authentication or role-based access control.
- Do not store sensitive employee or financial information in this demo.
- A production deployment should use a secure backend, database, password hashing, and proper access controls.

## 🧑‍💻 Customization

You can customize the project by changing:

- Employee name and employee ID
- Monthly salary and deduction percentage
- Standard working hours and work schedule
- Weekly off and leave allowance
- Public holidays and festivals
- UI theme and accent color

## 🗺️ Future Improvements

- Secure authentication with a backend
- Database integration and cloud synchronization
- Multiple employee accounts and admin roles
- PDF payslip generation
- Advanced attendance reports and charts
- Overtime and half-day calculations
- Import/export and restore from backup
- Mobile-friendly attendance entry

## 📸 Screenshots

Add screenshots of your application here after capturing them.

```md
![Login Page](screenshots/login.png)
![Dashboard](screenshots/dashboard.png)
![Attendance Page](screenshots/attendance.png)
![Monthly Payroll](screenshots/monthly-payroll.png)
```

## 🎯 Project Goal

The goal of this project is to simplify attendance tracking and payroll estimation through a clean dashboard, automated calculations, customizable settings, and downloadable reports.

## 📄 License

Choose a license before distributing this project publicly. For example, you can add an MIT License by creating a `LICENSE` file and including the appropriate license text.

---

**Built with ❤️ using HTML, CSS & JavaScript.**
