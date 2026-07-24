Electronics Sales Dashboard

An AI-powered web application developed to simplify electronics sales management through an intuitive dashboard, business analytics, and machine learning-based sales prediction. The project combines data management, visualization, and predictive analytics to help users monitor business performance and make informed decisions.



Project Overview

The Electronics Sales Dashboard is designed to provide a centralized platform for managing companies, products, customers, and sales orders. It offers real-time business insights through an interactive dashboard while integrating machine learning to forecast future sales trends.

The application was developed using Flask for the backend, SQLite for database management, and HTML, CSS, and JavaScript for the user interface. A Random Forest model is used to perform AI-based sales prediction.


Login Page

The application begins with a secure authentication system that restricts access to authorized users. This ensures that business information is protected while providing a clean and simple user experience.

![Login](login.png)


Dashboard

The dashboard provides a comprehensive overview of the business through key performance indicators, including total companies, customers, products, orders, revenue, and profit. It also includes search functionality, dark mode support, and report export capabilities to improve usability.

![Dashboard](dashboard.png)


Company Management

The Company Management module allows users to efficiently maintain company records. Users can add new companies, edit existing information, remove outdated records, and monitor revenue, profit, and order statistics from a single interface.

![Company Management](company.png)


Product Management

This module provides complete control over product information. Users can manage product details, maintain inventory records, and organize available products for efficient business operations.

![Products](products.png)


Customer Management

The Customer Management page enables efficient handling of customer information by allowing users to create, update, view, and remove customer records whenever required.

![Customers](customers.png)



Order Management

The Order Management module records customer orders and helps monitor sales activities. It provides an organized workflow for tracking transactions and managing business operations effectively.

![Orders](orders.png)



Analytics Dashboard

The Analytics section presents business data through interactive charts and graphical reports. These visualizations help users understand revenue patterns, business growth, and overall company performance.

![Analytics](analytics.png)


AI Sales Prediction

The application integrates a Machine Learning model based on the Random Forest algorithm to predict future sales using historical business data. This feature demonstrates the integration of artificial intelligence into traditional business management systems.

![AI Prediction](ai_prediction.png)


Company Details

The Company Details page displays detailed information about individual companies, including financial performance, revenue, profit, and order statistics, providing users with deeper business insights.

![Company Details](company_details.png)


Export Dashboard Report

Business reports can be exported in Excel format for documentation, record keeping, and further analysis outside the application.

![Export Report](export_report.png)


Key Features

- Secure user authentication
- Interactive business dashboard
- Company management system
- Product management
- Customer management
- Order management
- Business analytics with charts
- AI-based sales prediction using Random Forest
- Search functionality
- Dashboard report export
- Dark mode support
- Responsive user interface


Technology Stack

Backend
- Python
- Flask

Frontend
- HTML5
- CSS3
- JavaScript

Database
- SQLite

Machine Learning
- Scikit-learn (Random Forest)

Data Processing
- OpenPyXL
- Pandas
- NumPy



Project Structure

```
ElectronicsSalesDashboard
│
├── static/
├── templates/
├── database/
├── datasets/
├── model/
├── images/
├── app.py
├── requirements.txt
└── README.md
```

Getting Started

Clone the repository:

```bash
git clone https://github.com/Arshad2k57815/ElectronicsSalesDashboard.git
```

Navigate to the project directory:

```bash
cd ElectronicsSalesDashboard
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
python app.py
```

The application will be available at:

```
http://127.0.0.1:5000
```

Future Enhancements

- Advanced sales forecasting models
- Inventory management
- Customer purchase history
- Email notifications
- Cloud database integration
- Business performance reports
- Role-based user authentication


Developer

Kalimalla Arshad
B.Tech in Electrical and Electronics Engineering
IIIT RK Valley


Acknowledgements

This project was developed as part of my learning journey in **Flask web development, database management, business analytics, and machine learning integration. It demonstrates how data-driven technologies can be combined to build practical business management applications.
