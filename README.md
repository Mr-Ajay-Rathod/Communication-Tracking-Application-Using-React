# Communication Tracker Application

A modern React-based application designed to streamline and manage communication tracking for companies. This tool provides features for effective communication scheduling, insightful analytics, and intuitive calendar management, tailored for organizations of all sizes.

## **Features**

### **Admin Dashboard**
- **Company Management**: Add and manage company details.
- **Communication Insights**: Track contact information and preferences.
- **History Logs**: View complete communication history for each company.

### **Communication Tracking**
- Log past interactions and schedule future communications.
- Support for multi-company communication.
- Color-coded status indicators for clear tracking.

### **Interactive Calendar View**
- View communications in a dynamic calendar format.
- Events are color-coded by communication type.
- Clickable events reveal detailed information.
- Switch seamlessly between month, week, and day views.

### **Analytics Dashboard**
- Analyze communication frequency and engagement effectiveness.
- Monitor overdue communications and trends.
- Export customizable reports in PDF or CSV formats.

---

## **Prerequisites**

Ensure your system meets the following requirements before installation:
- **Node.js** (v14.0.0 or higher)
- **npm** (v6.0.0 or higher)

---

## **Installation Instructions**

### **Step 1: Clone the Repository**
```bash
https://github.com/Mr-Ajay-Rathod/Communication-Tracking-Application-Using-React.git
cd Communication-Tracking-Application-Using-React
```

### **Step 2: Install Dependencies**
```bash
npm install
```

### **Core Dependencies**
- **Material UI**: `npm install @mui/material @emotion/react @emotion/styled`
- **Redux Toolkit**: `npm install @reduxjs/toolkit react-redux`
- **Router**: `npm install react-router-dom`

### **Calendar Dependencies**
- **FullCalendar**: `npm install @fullcalendar/react @fullcalendar/daygrid @fullcalendar/timegrid @fullcalendar/interaction`

### **Chart Dependencies**
- **Recharts**: `npm install recharts`

### **Export Dependencies**
- **PDF/CSV Export**: `npm install jspdf jspdf-autotable`

### **Run the Application**
Start the development server:
```bash
npm start
```
By default, the application runs on **http://localhost:3000**.

---

## **Project Structure**

```
Communication-Tracker/
├── Public/
│   └── index.html
├── src/
│   ├── components/
│   │   ├── Admin/
│   │   ├── Analytics/
│   │   ├── Layout/
│   │   └── User/
│   ├── redux/
│   │   └── slices/
│   ├── App.js
│   ├── index.css
│   └── index.js
├── Package.json
└── Readme.md
```

---

## **Usage Guide**

### **Step 1: Admin Panel**
- Navigate to the Admin Dashboard to add companies and manage existing ones.
- Track contact details and communication preferences.

### **Step 2: Communication Tracking**
- Log past communications or schedule future ones.
- Manage multiple companies simultaneously.
- Use detailed notes and assign communication types.

### **Step 3: Calendar View**
- Visualize communications using the calendar interface.
- Toggle between month, week, and day views.
- Click events for detailed interaction information.

### **Step 4: Analytics Dashboard**
- Access engagement metrics and trends.
- Filter results by date range or company.
- Export reports for sharing and archiving.

---

## **Known Limitations**

1. **Data Persistence**
   - Data is stored in Redux state and localStorage.
   - No backend database; data may be lost if localStorage is cleared.

2. **Performance**
   - May slow down with extensive data.
   - Calendar performance is affected by numerous events.

3. **Browser Support**
   - Optimized for modern browsers like Chrome, Firefox, and Safari.
   - Limited support for older browsers.

4. **Calendar Features**
   - No drag-and-drop for event rescheduling.
   - Basic recurring event support.
   - No calendar sync features.

5. **Export Limitations**
   - Limited customization for PDF/CSV exports.
   - No direct email integration for reports.

---

## **Future Roadmap**

### **Backend Integration**
- Database storage.
- User authentication.
- API for real-time data sync.

### **Enhanced Features**
- Google/Outlook calendar sync.
- Email reminders and notifications.
- Advanced recurring events.
- Mobile application support.

### **Performance Optimization**
- Implement data pagination.
- Introduce lazy loading for faster rendering.
- Enable caching mechanisms.

---

## **Additional Features**

- **Dark Mode Support**: Seamless transition between light and dark themes.
- **Mobile Responsiveness**: Optimized design for tablets and smartphones.
- **User Roles**: Admin and user-level access permissions.
- **Search Functionality**: Quickly locate companies, events, or reports.

---

## **Contributions**
Contributions to this project are welcome! Feel free to fork the repository and create a pull request with your enhancements.

---

## **License**
This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## **Contact**
For any queries or feedback:
- **GitHub**: [Communication Tracker Repository](https://github.com/Mr-Ajay-Rathod/Communication-Tracking-Application-Using-React)

Elevate your communication management with **Communication Tracker** today!

