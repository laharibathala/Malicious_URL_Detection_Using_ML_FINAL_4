# Malicious URL Detection Using Machine Learning

## Project Overview
This project is a web-based application that detects whether a URL is malicious or legitimate using Machine Learning. It helps users identify phishing and harmful websites before accessing them.

## Features
- User Login and Registration
- URL Input and Prediction
- Detects Malicious or Legitimate URLs
- Machine Learning-based Prediction
- Django Web Application
- User-Friendly Interface

## Technologies Used
- Python
- Django
- Machine Learning
- Scikit-learn
- Pandas
- NumPy
- HTML
- CSS
- SQLite

## Project Structure

```
Project/
│── Remote_User/
│── Service_Provider/
│── Template/
│── detection_of_phishing_websites/
│── Detection_of_Phishing.py
│── manage.py
│── requirements.txt
│── README.md
```

## Installation

1. Clone the repository

```bash
git clone https://github.com/your-username/Malicious-URL-Detection.git
```

2. Move into the project directory

```bash
cd Malicious-URL-Detection
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

4. Run migrations

```bash
python manage.py migrate
```

5. Start the Django server

```bash
python manage.py runserver
```

6. Open your browser

```
http://127.0.0.1:8000/
```

## Machine Learning Model

The model is trained to classify URLs into:

- Legitimate URL
- Malicious URL

The prediction is displayed on the web interface after the user submits a URL.

## Future Enhancements

- Deep Learning Models
- Real-time URL Scanning
- Browser Extension
- API Integration
- Improved Accuracy

## Author

**Lahari**

B.Tech (Computer Science Engineering)

## License

This project is developed for educational purposes.
