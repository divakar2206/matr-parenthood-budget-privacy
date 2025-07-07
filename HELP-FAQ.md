# MATR Parenthood Budget – Help & FAQ

Welcome to the MATR Parenthood Budget Help & Frequently Asked Questions page!  
Below you'll find answers to common questions about using the app, features, troubleshooting, and more.

---

## Getting Started

### **How do I create my first budget?**
To create your first budget:
1. Open the app and log in or sign up.
2. On the dashboard, tap the "+" (FAB) button.
3. Choose "Monthly Budget" or "Budget Overview" to start planning your budget.

### **What happens if my profile is incomplete after login?**
If your profile is missing required information (like your display name or due date), the app will redirect you to the profile setup screen for onboarding before you can use other features.

---

## Features & Navigation

### **What’s the difference between User Mode and Admin Mode?**
- **User Mode:** Default for most users. Offers personal budget tracking, upcoming expenses, suggestions, and more.
- **Admin Mode:** Available to users with admin privileges. Lets you manage admins, the master checklist, and budget categories. You can switch between modes using the toggle in the dashboard or drawer (if you’re an admin).

### **What does the floating action button (FAB) do?**
The FAB provides quick access to key actions:
- Add Expense
- Checklist
- Budget Overview
- Monthly Budget
- Expense Tracker
- Settings
- Menu

Admins see additional shortcuts for admin tools.

### **How do I refresh my dashboard data?**
Pull down on the dashboard screen to refresh all key data: expenses, upcoming expenses, user role, profile completeness, and costliest upcoming expenses.

---

## Authentication & Account

### **How do I sign up for an account?**
1. Open the app and go to the authentication screen.
2. Enter your email and password.
3. Toggle to "Sign Up" mode and submit the form.
4. A new user account is created with the default "user" role.

### **What if I forget my password?**
Tap "Forgot Password" on the login screen. Enter your email and follow the steps to receive a password reset link.

### **Does MATR Parenthood Budget support social login (Google, Apple, etc.)?**
Currently, only email/password authentication is supported. Social login support may be added in the future.

### **How is my account role assigned?**
When you sign up, you’re assigned the "user" role by default. Admin roles are managed by other administrators.

---

## Budget Settings

### **How can I view, add, or edit my monthly budgets?**
- Go to the Budget Settings screen from the menu.
- See a list of all months with budgets.
- Tap the FAB to add a new monthly budget (manual entry or range).
- Tap any month card to edit its budget inline via a dialog.

### **Can I set budgets for a range of months at once?**
Yes! Use the "Entry from Range" option when tapping the FAB in Budget Settings. Select a start and end month/year, set the amount, and save—budgets for all those months will be created or updated.

### **What accessibility features are available in Budget Settings?**
- All buttons and interactive elements have semantic labels for screen readers.
- Logical keyboard navigation and focus order.
- Color contrast and font scaling follow the app theme.
- Feedback is provided for errors and success via snackbars.

---

## Error Handling & Troubleshooting

### **How does the app display errors?**
- For blocking or actionable errors, `AppErrorWidget` is shown (inline, fullscreen, dialog).
- For brief issues, a snackbar appears at the bottom with an error message.

### **What can I do if I see an error?**
- Use the "Retry" button if available.
- Use the "Feedback" button to report the issue (opens the GitHub Issues page).
- For dialog errors, tap "Dismiss" or "Close".

### **How can I report a bug or give feedback?**
Use the feedback option in error dialogs or email us at [glow.forge.dev@gmail.com](mailto:glow.forge.dev@gmail.com).

---

## Data & Privacy

### **Where is my data stored and is it secure?**
- All your personal data and expenses are stored **locally on your device**.
- Some anonymized usage data may be collected to improve the app.
- See our [Privacy Policy](https://raw.githubusercontent.com/divakar2206/matr-parenthood-budget-privacy/main/privacy-policy.md) for details.

### **What happens to my data if I uninstall the app?**
All locally stored data will be deleted if you uninstall the app.

### **Is any of my data shared with third parties?**
No. Your personal data is not sold, traded, or shared, except as required by law.

---

## App Store & Release

### **Where can I find the privacy policy?**
The privacy policy is available both in the app and at  
[https://raw.githubusercontent.com/divakar2206/matr-parenthood-budget-privacy/main/privacy-policy.md](https://raw.githubusercontent.com/divakar2206/matr-parenthood-budget-privacy/main/privacy-policy.md)

### **What assets are needed for the Google Play Store listing?**
- App icon (512x512)
- Feature graphic (1024x500)
- 5–8 screenshots (16:9–9:16 aspect ratio)
- App description, privacy policy link, and optional promo video

See [assets/app_store_assets.md](https://github.com/divakar2206/matr_parenthood_budget/blob/main/assets/app_store_assets.md) for full details.

---

## Firestore & Data Model

### **What information is stored in Firestore?**
- User profile (`displayName`, `email`, `role`, etc.)
- Expenses, budget categories, monthly budgets, and checklist items
- Only authenticated users can read/write their own data

See [docs/firestore_schema.md](https://github.com/divakar2206/matr_parenthood_budget/blob/main/docs/firestore_schema.md) for details.

---

## General

### **Where can I find project documentation or feature breakdowns?**
See the [docs/](https://github.com/divakar2206/matr_parenthood_budget/tree/main/docs) directory in the repository for detailed documentation on features, UI flows, and implementation.

### **How can I suggest a new feature or report a bug?**
- Visit the [Issues page on GitHub](https://github.com/divakar2206/matr_parenthood_budget/issues)
- Or email us at [glow.forge.dev@gmail.com](mailto:glow.forge.dev@gmail.com)

---

## Need more help?
If your question is not answered here, please reach out via email or open an issue on GitHub.  
We're here to help!

---
_Last updated: July 7, 2025_
