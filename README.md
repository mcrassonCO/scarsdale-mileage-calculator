# 🚗 Scarsdale Schools - Official Mileage Calculator

A premium, high-fidelity web application built for **Scarsdale Union Free School District** employees to calculate personal vehicle mileage reimbursement. It dynamically computes and compares route distances to ensure compliance with the district's reimbursement policy.

---

## 🌟 Key Features

* **Dual-Origin Route Verification:** Automatically calculates and displays maps for both **Home Origin** and **School Origin** to the destination.
* **Lesser-Of-Two Policy Compliance:** Automatically determines the lesser roundtrip distance between the two origins for reimbursement calculations.
* **Multi-Stop Journeys:** Supports adding optional stops along both the outbound and return journeys.
* **Two-Column Side-by-Side Journeys:** Visualizes outbound and return legs side-by-side, detailing geocoded addresses clearly.
* **Intelligent Address Parsing:** Strips verbose geocoder metadata to show clean, compact addresses.
* **Consolidated Manual Override:** Allows employees to override mileage manually with actual driven miles and detour justifications.
* **Single-Page Portrait Printing:** Optimized CSS stylesheets format the results into a beautiful, official 8.5" x 11" letter page print layout.

---

## 📋 How It Works (Policy Rules)

The system calculates reimbursement based on the **lesser** of two roundtrip options:
1. **Home Origin:** Home ➔ [Optional Outbound Stop] ➔ Destination ➔ [Optional Return Stop] ➔ Home.
2. **School Origin:** School Building ➔ [Optional Outbound Stop] ➔ Destination ➔ [Optional Return Stop] ➔ School Building.

- **Reimbursement Mileage:** `min(Home Roundtrip, School Roundtrip)`
- **Reimbursement Amount:** `Reimbursement Mileage * IRS 2026 Mileage Rate ($0.725/mi)`

---

## 🚀 How to Publish on GitHub Pages

Publish this calculator instantly for free using GitHub Pages:

1. Push your `index.html` and `README.md` to your public GitHub repository (`scarsdale-mileage-calculator`).
2. Go to the repository **Settings** tab.
3. Scroll down to the **Pages** menu on the left sidebar.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Set the branch to `main` (or `master`) and the folder to `/ (root)`.
6. Click **Save**.
7. Within 1-2 minutes, GitHub will publish your site at `https://<your-username>.github.io/scarsdale-mileage-calculator/`.

---

## 💻 Running Locally

To run the application on your computer:

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/scarsdale-mileage-calculator.git
