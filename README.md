# School App & Subscription Directory

A simple web tool for schools to keep track of digital applications and online subscriptions.  
This project was created to help staff quickly **find, filter, and explore** the tools available in our school.

👉 **Live site:** [View on GitHub Pages](https://mrsidneytech-dev.github.io/app-directory/)

---

## ✨ What it does

- Shows all of our applications/subscriptions in a **visual card layout** with:
  - Thumbnail image (logo or screenshot)
  - Title
  - Short description
  - Tags (e.g. AI, Productivity, Mind Map)
  - Department (e.g. Science, Maths, English)
  - Status (Active, Being Purchased, Under Process, Expired)

- Provides **search and filters** so teachers can:
  - Search by name, description, or tag
  - Filter by department
  - Filter by tags
  - Filter by subscription status
  - Combine filters together

- Supports **pagination** (up to 100 apps per page)  
- Mobile-friendly, works on any device  
- Admins can **edit or replace the dataset** with their own JSON or CSV file  

---

## 🎯 Why it’s useful in a school context

- Helps teachers **see what tools are already licensed or supported** without needing to ask IT.
- Makes it easier to discover tools by subject area or teaching strategy.
- Provides clarity on **status** of tools (e.g. whether something is available yet).
- Can reduce duplicate subscription requests or confusion about which tools are approved.

---

## 🛠 How to use / customise

1. **View the live directory**  
   Open the [GitHub Pages link](https://mrsidneytech-dev.github.io/app-directory/).

2. **Search & filter**  
   Try searching for “AI” or filtering by your department.

3. **Update the dataset**  
   - The data powering the directory lives in a simple **CSV file** added as a file in this repository.  
   - To make updates:
     1. Open the CSV file in the repo (e.g. `apps-data.csv`) or in Excel/Google Sheets
     2. Click the pencil icon in GitHub to edit directly in the browser, or upload a new version.
     3. Commit your changes.
   - Within a few minutes, the live site on GitHub Pages will automatically pull the updated CSV.  
   - This means non-technical staff can maintain the list just by editing a spreadsheet.

4. **Add your own images**  
   - Ideal thumbnail size: **176 × 128 pixels** (keeps them sharp on mobile and desktop).
   - Save them in an `images/` folder in this repo or in Google Drive and link to them in your dataset.

---

## 📦 Hosting & embedding

- The site is hosted on **GitHub Pages** (free).  
- You can embed it in a **Google Site** (Insert → Embed → By URL).  
- Other hosting options: Netlify, Vercel, or any static web server.

---

## 💡 Ideas for other teachers

- Use it as a **departmental app directory** (e.g. just Maths tools).  
- Create a **shared “approved tools” hub** for your staffroom.  
- Build a student-facing version so they know what tools are available.  
- Maintain a “wishlist” of tools under consideration.  

---

## 🙌 Contributing

If you’d like to adapt this for your own school:
- Fork the repo
- Replace the sample data with your own
- Share your version with colleagues

Feedback and improvements are welcome!

---

## 📄 License

This project is shared under the Creative Commons License — feel free to reuse and adapt.
