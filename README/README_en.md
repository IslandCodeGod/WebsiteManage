# Flask Web Application - Enterprise website management system (encrypted version)

## Project Introduction

This is an **encrypted version** of an enterprise website management system developed based on the Flask framework. The core code has been obfuscated and encrypted by PyArmor to protect intellectual property rights.The system supports multi-language (Chinese and English), user authentication, product and news management, company information display and other functions.

## Application screenshot

The following is a screenshot of the main interface of the application:

### Home
![首页](screenshots/index.png)

### Management background
![管理后台](screenshots/admin_dashboard.png)

## Release Notes

This version is a basic encryption version that provides complete corporate website management functions.If you need:

- **Complete source code version**: Contains unencrypted complete source code to facilitate secondary development
- **Customized Function Development**: Function customization and expansion according to your specific needs
- **Technical Support Services**: Get professional technical support and maintenance services

Please contact us through the contact information below and we will provide you with detailed plans and quotations.

## Encryption features

- **Code Protection**: Core Python files (app.py, init_db.py, models.py) are obfuscated and encrypted
- **Runtime Protection**: Use the PyArmor runtime environment to prevent code from being decompiled
- **Full functionality**: The encrypted code maintains all original functionality and features
- **Multi-language support**: built-in Chinese and English switching function

## Include files

```
/
├── app.py                  # Encrypted main application entry
├── init_db.py              # Encrypted database initialization script
├── models.py               # Encrypted data models
├── babel.cfg               # Babel internationalization configuration
├── pyarmor_runtime_000000/ # PyArmor runtime support files
├── static/                 # Static resource files (CSS, JS, images)
├── templates/              # HTML template files
├── translations/           # Multi-language translation files
└── instance/               # Database directory (automatically created on first run)
```

## Quick Start

### Environmental requirements

- Python 3.9 or higher
- Installed dependency packages:
- Flask 3.0.0+
- Flask-SQLAlchemy 3.1.1+
- Flask-Login 0.6.3+
- Flask-Babel 4.0.0+
- Werkzeug 3.0.1+

### Install dependencies

If the required dependencies are not installed yet, please install them first:

```bash
pip install flask flask-sqlalchemy flask-login flask-babel werkzeug
```

### Run the application

1. **Initialize database**

Before running for the first time, the database needs to be initialized:

```bash
   python init_db.py
   ```

2. **Launch the application**

```bash
   python app.py
   ```

3. **Access App**

Open the browser and visit: http://127.0.0.1:5000

## Instructions for use

### Visit website

1. Open the browser and visit http://127.0.0.1:5000
2. Use the language switch button in the upper right corner to switch between Chinese and English

### Management background

1. Visit http://127.0.0.1:5000/admin/login
2. Log in with the administrator account (default username and password: admin/admin123)
3. Products, news and company information can be managed in the management background

## Function description

### Front-end functions

- **Home**: Display company profile and main products
- **About Us**: Show company details
- **Product Display**: Browse all product listings
- **Industry Updates**: View the latest news and information
- **Language switching**: Supports switching between Chinese and English

### Manage background functions

- **Product Management**: Add, edit, delete products
- **News Management**: Publish, edit, delete news
- **Company Information**: Update basic company information
- **User Authentication**: secure login system

## Screenshot Guide

In order to get the best README display effect, it is recommended to create and add screenshots according to the following guidelines:

1. **Create screenshots folder**: Create the `screenshots/` folder in the `dist/` directory
2. **Screenshot Size**: Use a screenshot with 1920x1080 or 1366x768 resolution to ensure the content is clearly visible
3. **Screenshot content**:
- Home page: Displays the complete home page interface, including navigation bar and main content area
- Language switching: Show the comparative effect of switching between Chinese and English (split-screen screenshots can be used)
- Product display: display product list and details of individual products
- News page: display news list and news details
- Management backend: displays the dashboard and functional interface after the administrator logs in
4. **Screenshot Format**: Use PNG format for best quality
5. **File Naming**: Save the screenshot according to the file name specified in the README (index.png, language_switch.png, etc.)

## Notes

1. **File Integrity**: Please ensure that all files have been downloaded correctly, especially the `pyarmor_runtime_000000` directory and its contents

2. **Database file**:
- The database file will be automatically created in the `instance` directory
- If you need to back up data, please back up the `instance/site.db` file regularly

3. **Multi-language support**:
- All translation files are included in the `translations` directory
- To add new translation languages, please refer to the original project documentation

4. **Operating environment**:
- Make sure the Python version is no lower than 3.9
- Make sure all necessary dependencies are installed

5. **Safety Tips**:
- When deploying to a production environment, please change the default administrator password.
- Consider using a WSGI server (such as Gunicorn) instead of the development server
- Configure appropriate firewall rules

## Deployment recommendations

### Development environment

Use the Flask built-in development server (shown in the quick start above).

### Production environment

1. **Use WSGI server**:
```bash
   pip install gunicorn
   gunicorn -w 4 -b 0.0.0.0:8000 app:app
   ```

2. **Use reverse proxy**:
- Configure Nginx or Apache as a reverse proxy
- Set up SSL certificate to enable HTTPS

3. **Database Optimization**:
- Consider using PostgreSQL or MySQL instead of SQLite
- Configure regular backup mechanism

## Troubleshooting

### FAQ

1. **Application cannot be started**:
- Check whether the Python version meets the requirements
- Confirm that all dependent packages are installed correctly
- Check whether the `pyarmor_runtime_000000` directory exists and is complete

2. **Language switching not working**:
- Confirm that the `translations` directory and its contents are complete
- Check whether browser Cookies settings are allowed

3. **Database connection error**:
- Confirm that the `instance` directory exists and has write permissions
- Try re-running `init_db.py` to initialize the database

### Log View

When the application starts, log information will be output on the console. If you encounter problems, you can check these logs for more information.

## License

[MIT License](LICENSE)

## Contact information

If you have any questions, suggestions, or need full version/customized function development, please contact via the following methods:

- **Email**: austinlive666@gmail.com (recommended)
- **Discord**:[https://discord.gg/7AN9PuGn](https://discord.gg/7AN9PuGn)

---

Thanks for using this project!