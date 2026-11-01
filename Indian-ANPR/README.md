<div align="center">

<h1>🚗 Indian Automatic Number Plate Recognition</h1>
<h3><code>From plate text to registration checks</code></h3>

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=900&lines=From%20plate%20text%20to%20registration%20checks;Learn+it.+Build+it.+Explain+it." alt="From plate text to registration checks" />

<p>
<img src="https://img.shields.io/badge/Computer%20Vision-6E40C9?style=for-the-badge" alt="Computer Vision" />
<img src="https://img.shields.io/badge/Maintained%20by%20Somil%20Singh-58A6FF?style=for-the-badge&logo=github&logoColor=white" alt="Maintained by Somil Singh" />

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge" alt="Python" />
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge" alt="Node.js" />
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge" alt="MySQL" />
<img src="https://img.shields.io/badge/HTML-E34F26?style=for-the-badge" alt="HTML" />
</p>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/somil-singh)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:somils@andrew.cmu.edu)
[![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/Skywalkerlyzv)
[![Medium](https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@thesomilsinghofficial)
[![Substack](https://img.shields.io/badge/Substack-FF6719?style=for-the-badge&logo=substack&logoColor=white)](https://thesomilsingh.substack.com/)

[Open this project](https://github.com/somilsin/Computer-Vision/tree/main/Indian-ANPR) · [My GitHub](https://github.com/somilsin) · [Main Portfolio](https://somilsin.github.io/Artificial-Intelligence/portfolio/)

</div>

<br>

I built this project to connect number plate recognition with vehicle registration records. It reads a plate from an image, looks up the registration in MySQL and can send an SMS alert through Twilio.

## 🔎 The pipeline

* OpenCV processes the image and pytesseract reads the plate text.
* MySQL stores vehicle and owner records for the registration check.
* The browser interface provides the user and admin pages.
* Twilio handles the configured text alerts.

## 📂 Where to start

| File | What it's for |
| :--- | :--- |
| [main1.py](main1.py) | Python recognition and registration logic. |
| [app.js](app.js) | Node.js application. |
| [package.json](package.json) | Node dependencies and scripts. |
| [tables.txt](tables.txt) | Database table definitions. |
| [HTML/](HTML/) | User and admin pages. |

## ⚙️ Configuration

Set these environment variables locally before running the relevant program:

* `MYSQL_PASSWORD`
* `TWILIO_ACCOUNT_SID`
* `TWILIO_AUTH_TOKEN`
* `TWILIO_FROM_NUMBER`
* `TWILIO_TO_NUMBER`

The Python program can send SMS messages so check the recipient and database configuration before running it. Keep the actual credentials out of the repo.
