
# 🔗 LinkedIn Profile Scraper

A simple LinkedIn profile scraper built with **Selenium**, **BeautifulSoup**, and **Python**.

👉 This tool logs into LinkedIn, searches for a user-specified keyword (e.g. "Software Engineer"), and extracts profile URLs, names, job titles, and locations. The data is saved to a CSV file.

⚠️ **Disclaimer:**
This project is for educational purposes only. Scraping LinkedIn violates their [Terms of Service](https://www.linkedin.com/legal/user-agreement). Use responsibly and at your own risk.

---

## 📌 Features

* Log in to LinkedIn automatically using Selenium.
* Search for profiles based on your query.
* Navigate through multiple search result pages.
* Extract profile URLs, names, job titles, and locations.
* Save the results in a CSV file.

---

## 🛠 Requirements

* Python 3.x
* Chrome browser
* ChromeDriver

### Python libraries:

```bash
pip install selenium beautifulsoup4
```

---

## 🚀 How to Use

1️⃣ Clone this repository:

```bash
git clone https://github.com/your-username/linkedin-scraper.git
cd linkedin-scraper
```

2️⃣ Update your LinkedIn credentials in the script:

```python
email_field.send_keys("YOUR_EMAIL_HERE")
password_field.send_keys("YOUR_PASSWORD_HERE")
```

3️⃣ Run the script:

```bash
python linkedin_scraper.py
```

4️⃣ Follow the prompts:

* Enter the search query (e.g. *Software Engineer*).
* Enter the number of pages you want to scrape.

5️⃣ The scraped data will be saved in:

```
output1.csv
```

---

## 📂 Output Example

| Name     | Job Title                | Location          | URL                                                                        |
| -------- | ------------------------ | ----------------- | -------------------------------------------------------------------------- |
| John Doe | Software Engineer at XYZ | San Francisco, CA | [https://www.linkedin.com/in/johndoe](https://www.linkedin.com/in/johndoe) |

---

## ⚠️ Important Notes

* LinkedIn’s anti-bot measures may block or restrict your account. Consider using proxies, delays, or other safety measures if you explore automation further.
* Do **not** use this on accounts you care about without understanding the risks.
* Always comply with LinkedIn's [terms](https://www.linkedin.com/legal/user-agreement) and local laws.

---

## 🤝 Contributions

Feel free to fork this repository and submit pull requests!

---

## 📄 License

This project is licensed under the MIT License.

