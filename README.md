# 💻 Laptop Recommendation System (Flask App)

This is the Day 3 project of a winter bootcamp: a laptop recommendation system built using Python and Flask.  
The app allows users to input preferences such as **budget**, **memory**, **brand**, **screen size**, and **OS**,  
then recommends suitable laptop models based on a scoring system.

---

## 📅 Date  
**January 20, 2025 (Day 3)**

---


## 🚀 Features

- ✅ Editable laptop data through web interface
- ✅ Automatically generates brand options from the data (not hardcoded)
- ✅ Budget field can be left blank (treated as no budget limit)
- ✅ Memory unit supports MB / GB / TB with automatic conversion
- ✅ Recommends **all laptops** that score 3 or more points
- ✅ Displays how well each laptop matches your criteria
- ✅ Clickable product links (URL from the last column)

---

## 📁 Data Format (items.txt)

You must provide a file named `items.txt` that contains laptop data.  
Each line represents a laptop, with fields separated by commas `,`, and **each line ends with a semicolon `;`**, except the last line.

### Format:
```
Model,Price,Memory,Brand,ScreenSize,OS,Link
```

### 🧾 Example:
```
ZenBook14,30000,512GB,ASUS,14.0,Windows,https://www.asus.com/Laptops/Zenbook-14;
MacBookAir,42000,256GB,Apple,13.3,MacOS,https://www.apple.com/macbook-air;
Gram16,38000,1TB,LG,16.0,Windows,https://www.lg.com/laptops/lg-gram-16;
SurfaceLaptop5,45000,512GB,Microsoft,15.0,Windows,https://www.microsoft.com/surface-laptop-5;
MacBookPro,62000,1TB,Apple,16.2,MacOS,https://www.apple.com/macbook-pro
```

---

## ▶️ How to Run

1. Make sure you have Python and Flask installed:
   ```bash
   pip install flask
   ```

2. Put your `items.txt` in the same folder as `app.py`.

3. Run the app:
   ```bash
   python app.py
   ```

4. Open your browser and go to:
   ```
   http://127.0.0.1:5000/list
   ```

---

## 🛫 GitHub Submission Guide

### ✅ First-time upload

```bash
git init
git add .
git commit -m "Initial commit - Laptop recommendation system"
git branch -M main
git remote add origin https://github.com/your-username/your-repo-name.git
git push -u origin main
```

### ✅ Later updates

```bash
git add .
git commit -m "Update scoring logic and display multiple results"
git push
```

---

This project demonstrates how Python and Flask can be used to build a smart, user-friendly recommendation system.  
Great for school projects, learning Flask, or just geeking out about laptops 😎
