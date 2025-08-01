# Zomato Power BI Dashboard

[➡️ **Live Power BI Dashboard**](https://app.powerbi.com/view?r=eyJrIjoiNmYzYmNjNDYtNGI2OC00NTMyLTg4M2QtZmZmZTU5MDRhNTMxIiwidCI6ImRkM2E5NTVkLWFiNzMtNGU4OC1hNDdhLTQ1ZGUyNWE5MjViZCJ9&pageName=a85c741bf1cc544e1dcc)

---

## 🚀 Tech Stack
<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" alt="Figma"/>
</p>

---

## 📑 Features
- **Live Power BI Dashboard**: Embedded Power BI report for real-time data visualization.
- **Sales Overview**: Analyze sales trends, peak periods, and revenue drivers.
- **Overview Report**: High-level business performance metrics.
- **Customer Report**: Insights into customer behavior, loyalty, and demographics.
- **Inventory Report**: Track operational KPIs and workflow efficiency.
- **Marketing Report**: Evaluate campaign effectiveness and marketing ROI.
- **Skills Section**: Highlights key technologies used.
- **Responsive Design**: Optimized for desktop and mobile devices.
- **Social Links**: Quick access to LinkedIn, GitHub, and email.

---

## 🛠️ How to Set Up This Project
1. **Clone the repository**
   ```bash
   git clone <repo-url>
   cd "Zomato Dashboard"
   ```
2. **Open `Index.html` in your browser**
   - Double-click or right-click and open with your preferred browser.
3. **Power BI Dashboard**
   - The embedded dashboard uses a published Power BI report. To use your own, update the `src` attribute of the `<iframe>` in `Index.html` with your Power BI report link.
4. **Data Files**
   - All relevant data files are in the `data/` folder. You can update these as needed for your own analysis.
5. **Excel Uploader (Optional)**
   - If you want to upload new Excel files, use the Flask app in `data/excel_uploader/`.
   - Make sure you have Python installed, then run:
     ```bash
     cd data/excel_uploader
     pip install -r requirements.txt
     python app.py
     ```
   - Access the uploader at `http://localhost:5000` in your browser.

---


## 📂 Project Structure
```
Zomato Dashboard/
├── .git/                # Git version control folder
├── Index.html           # Main web page
├── README.md            # Project documentation
├── pictures/            # Images for dashboard and preview
│   ├── city.png
│   ├── home.png
│   ├── overview.png
│   ├── SG web.jpeg
│   └── user.png
```

---

##  Author
- **Santosh Kumar**
- [LinkedIn](https://www.linkedin.com/in/santosh-kumar-787234341/)
- [GitHub](https://github.com/SantoshGorebal007)

---

## 📄 License
This project is for educational and portfolio purposes.

---

## 🏠 Home Preview
![Home Preview](pictures/home.png)

## 📊 Overview Performance
![Overview Performance](pictures/overview.png)

## 👤 User Performance
![User Performance](pictures/user.png)

## 🏙️ City Performance
![City Performance](pictures/city.png)
