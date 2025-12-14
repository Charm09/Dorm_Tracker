# 🏠 Dorm Budget Tracker

A comprehensive expense tracking and budget management application designed specifically for dormitory students. Built with Python and Tkinter, featuring both user and admin interfaces with robust data visualization and reporting capabilities.

![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20macOS-lightgrey)

## ✨ Features

### 👤 User Features
- **Budget Management**
  - Set monthly budget and savings targets
  - Track daily spending allowance
  - Real-time budget calculations
  - Visual progress indicators

- **Expense Tracking**
  - Quick expense entry with calendar picker
  - Categorized expenses (Food, Transportation, Utilities, etc.)
  - Edit and delete expense entries
  - Search and filter expense history

- **Reports & Analytics**
  - Monthly expense summaries
  - Category-wise spending analysis
  - 6-month spending trends
  - Daily spending patterns
  - Budget utilization statistics

- **Visualizations**
  - Interactive pie charts
  - Bar graphs for comparisons
  - Line charts for trends
  - Category distribution analysis

- **Data Export**
  - Export expenses to CSV
  - Generate detailed reports
  - Backup personal data

### 👔 Admin Features
- **User Management**
  - Create, edit, and manage user accounts
  - Activate/deactivate users
  - Reset user passwords
  - View user statistics

- **System Monitoring**
  - Real-time system overview
  - Activity logging and tracking
  - User engagement metrics
  - Database statistics

- **Database Tools**
  - Backup and restore database
  - Optimize database performance
  - Integrity checks
  - SQL query interface
  - Import/export data

- **Reporting**
  - System-wide reports
  - User activity analysis
  - Expense analytics across all users
  - Export system data

## 🚀 Installation

### Prerequisites
- Python 3.8 or higher
- pip (Python package installer)

### Required Libraries
```bash
pip install -r requirements.txt
```

Or install individually:
```bash
pip install tkcalendar
pip install matplotlib
pip install pandas
```

### Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/dorm-budget-tracker.git
   cd dorm-budget-tracker
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application**
   ```bash
   python dorm_tracker.py
   ```

## 📋 Default Credentials

### Admin Login
- **Email:** `admin@dormtracker.com`
- **Password:** `admin123`

⚠️ **Important:** Change the default admin password immediately after first login!

## 🎯 Quick Start Guide

### For Students

1. **Sign Up**
   - Click "Create Account" on the main screen
   - Fill in username and password (minimum 6 characters)
   - Optionally add email

2. **Complete Profile**
   - Set your monthly budget
   - Set savings target
   - Enter your full name

3. **Add Expenses**
   - Click "➕ Add Expense" button
   - Select date from calendar
   - Choose category
   - Enter item name and amount
   - Click "Save Expense"

4. **View Reports**
   - Access monthly summaries
   - Check category breakdowns
   - View spending trends
   - Export data to CSV

### For Administrators

1. **Login**
   - Select "Admin Login"
   - Use admin credentials

2. **Manage Users**
   - View all registered users
   - Edit user details
   - Activate/deactivate accounts
   - Reset passwords

3. **Monitor System**
   - Check system overview
   - View activity logs
   - Generate reports

4. **Database Maintenance**
   - Create backups
   - Optimize database
   - Run integrity checks

## 📊 Budget Calculations

The application uses the following formulas:

```
Spendable Amount = Monthly Budget - Target Savings
Remaining Budget = Spendable Amount - Spent This Month
Daily Allowance = Remaining Budget ÷ Days Left in Month
Budget Used % = (Spent This Month ÷ Monthly Budget) × 100
```

## 📁 Project Structure

```
dorm-budget-tracker/
│
├── dorm_tracker.py          # Main application file
├── dorm_tracker.db          # SQLite database (auto-created)
├── requirements.txt         # Python dependencies
├── README.md               # This file
└── LICENSE                 # License file
```

## 🗄️ Database Schema

### Tables
- **users** - User accounts and profile information
- **admins** - Administrator accounts
- **entries** - Expense records
- **activity_logs** - System activity tracking
- **system_settings** - Application configuration

## 🎨 Themes

The application features three distinct themes:

1. **Main Theme** - Clean blue interface for login screens
2. **User Theme** - Soft pink theme for user dashboard
3. **Admin Theme** - Professional gray-blue theme for admin panel

## 🔒 Security Features

- Password hashing using SHA-256
- Input validation and sanitization
- User account activation control
- Activity logging for all actions
- Session management
- SQL injection prevention

## 📈 Export Formats

- **CSV** - Expense history, reports
- **Database Backups** - Complete data backup
- **Text Reports** - Formatted system statistics

## 🛠️ Technologies Used

- **Python 3.8+** - Core programming language
- **Tkinter** - GUI framework
- **SQLite3** - Database management
- **Matplotlib** - Data visualization
- **Pandas** - Data manipulation
- **tkcalendar** - Calendar widget

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 Future Enhancements

- [ ] Multi-currency support
- [ ] Mobile app version
- [ ] Cloud synchronization
- [ ] Receipt photo uploads
- [ ] Budget recommendations using ML
- [ ] Email notifications
- [ ] Recurring expense tracking
- [ ] Shared expenses for roommates
- [ ] Goal setting and tracking
- [ ] Dark mode

## 🐛 Known Issues

- None currently reported

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

Your Name
- GitHub: [@yourusername](https://github.com/yourusername)
- Email: your.email@example.com

## 🙏 Acknowledgments

- Inspired by the needs of college dormitory students
- Built with Python's excellent GUI and data libraries
- Special thanks to the open-source community

## 📞 Support

For support, email your.email@example.com or open an issue in the GitHub repository.

## 🔄 Version History

### Version 1.0.0 (Current)
- Initial release
- User expense tracking
- Admin panel
- Report generation
- Data visualization
- Database management tools

---

**Made with ❤️ for students managing their dorm budgets**