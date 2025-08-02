💻 BrandZone – Landing Page
Welcome to BrandZone, a responsive landing page project designed using HTML and CSS. This project showcases services and allows users to send feedback through a fully functional contact form integrated with Formspree.

📌 Project Overview
This project is a simple, professional landing page that includes:

Modern navigation bar

"About Us", "Services", and "Contact Us" sections

Feedback/contact form with email notification using Formspree

Clean layout with responsive design

🚀 Technologies Used
✅ HTML5

✅ CSS3 (with Flexbox & Grid)

✅ Formspree for handling form submissions

📁 Folder Structure
pgsql
Copy
Edit
/BrandZone
├── index.html         → Main website
├── style.css          → Stylesheet
├── thank-you.html     → Page shown after successful submission
├── images/            → Contains profile and other images
📬 Contact Form (via Formspree)
The form submits data to your Formspree project using POST and sends the form input to your email.

html
Copy
Edit
<form action="https://formspree.io/f/your_form_id" method="POST">
  <input type="text" name="name" placeholder="Your Name" required>
  <input type="email" name="email" placeholder="Your Email" required>
  <textarea name="message" placeholder="Your Feedback" required></textarea>
  <button type="submit">Submit</button>
</form>
✅ You will receive an email notification for every successful submission.

🧪 How to Run
Download or clone the repository.

Open index.html in any modern browser.

Fill in the form and hit submit.

After submitting, you'll see a thank-you page and receive an email (if integrated correctly).

📸 Screenshots
You can add screenshots here of your landing page and form UI.

🏁 Status
✔️ Project Completed
✔️ Mobile Responsive
✔️ Integrated with Formspree

