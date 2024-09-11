# Sign Up Page

A fully functional sign-up and sign-in page with validation and email notification features. The project also includes a forget password page where users can reset their password. This project uses SweetAlert for form validation alerts and SMTP.js for sending email data to the administrator.

## Features

- Responsive Sign-Up and Sign-In forms.
- Email validation and input field checks.
- Forget password functionality with OTP input.
- Email notification system for handling form data using SMTP.js.
- Smooth page transitions between Sign-Up, Sign-In, and Forget Password forms.
- Friendly error and success messages using SweetAlert.

## Technologies Used

- HTML5
- CSS3
- JavaScript
- SweetAlert
- SMTP.js

## Installation

Clone the repository and open the project in your preferred code editor.

```bash
git clone https://github.com/Ashfaque3777/Sign-up_Page.git
cd Sign-up_Page
```

## How to Use

1. **Sign Up:**

   - Enter email, first name, last name, phone number, and password.
   - Submit the form to send data via email.

2. **Sign In:**

   - Enter your email and password to log in.
   - Data will be sent to the admin's email via SMTP.js.

3. **Forget Password:**
   - Enter your email and OTP to reset your password.
   - The new password and OTP will be sent to the admin's email.

## Demo

You can view a live demo of the project [here](https://sign-up-page-197786.netlify.app).

## Future Enhancements

- **Password Strength Indicator:** Add a visual indicator for password strength.
- **Multi-step OTP Verification:** Implement multi-step verification for stronger security.
- **Database Integration:** Store user data in a database instead of sending it via email.
- **Improved UI:** Add animations for a smoother user experience and a more modern design.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/new-feature`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/new-feature`).
6. Open a pull request.

```bash
# Clone the repository
git clone https://github.com/Ashfaque3777/Sign-up_Page.git

# Create a new branch
git checkout -b feature/new-feature

# Make changes and commit
git add .
git commit -m "Add new feature"

# Push to the branch
git push origin feature/new-feature

# Open a pull request
```

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.
