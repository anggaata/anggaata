# Hey there! 👋 Welcome to My GitHub

I'm **Angga**, a passionate **Full Stack Web Developer** with over a decade of experience in building and optimizing web applications. From crafting beautiful front-end designs to making sure the back-end runs like a well-oiled machine, I love taking on challenges and delivering top-notch results.

## 💻 What I Do

- **Frontend Magic** 🪄: Vue.js, React, JavaScript, HTML5, CSS3, and a bit of Angular to make things pop.
- **Backend Wizardry** 🔧: PHP, Node.js, Python, Laravel, MySQL, Postgresql, and MongoDB to keep the server-side smooth and scalable.
- **CMS Mastery** 🛠️: WordPress, WooCommerce, Django CMS, Shopify—you name it, I can probably make it work.
- **Build & Deploy** 🚀: Git, GitHub, and the usual suspects to get things up and running without a hitch.


## 🚀 Projects I’ve Worked On

I’ve been lucky to work on a variety of cool projects, from developing fully customized eCommerce platforms to building APIs and creating unique solutions for businesses around the world. Here are some highlights:

- Built an eCommerce platform on **Django CMS** that automates deployments and plugin installations.
- Helped a healthcare startup redesign their site, boosting performance and UX using **JavaScript**, **PHP**, and **MySQL**.
- As a startup founder, I launched and scaled fully customized eCommerce stores on WooCommerce and WordPress. I didn’t just use pre-built themes and plugins—I crafted unique, tailor-made solutions that enhanced customer experience and optimized sales processes. Through extensive customization of themes, plugins, and site functionalities, my work made it almost impossible to tell these stores were powered by WordPress and WooCommerce. I also drove successful digital marketing campaigns using Google Ads and Facebook Ads, alongside SEO strategies that boosted online visibility and conversions.

### Want to check out my work? Take a look at my pinned repositories below or browse around! 😄

## 📫 Let's Collaborate!

If you’re looking for a reliable, creative, and detail-oriented developer who can help bring your project to life, I’d love to chat! I’m always open to new challenges, freelance opportunities, or just geeking out about tech. Hit me up:

- **Email**: [Mail Me!](mailto:contact@anggaata.com)
- **LinkedIn**: [Lets Connects!](https://www.linkedin.com/in/eka-s-70503119a)
- **Website**: [Visit My Site!](https://anggaata.com)

## 🌟 Skills & Tools

Here's a quick overview of what I bring to the table:

- **Frontend**: Vue.js, React, HTML5, CSS3, JavaScript, jQuery, Next
- **Backend**: PHP, Node.js, Python, Laravel, MySQL, MongoDB, Postgresql
- **CMS**: WordPress, WooCommerce, Django CMS, Shopify, Webflow
- **Tools**: Git, GitHub, Docker, NPM, cPanel, Google Analytics, Google Tag Manager, Hotjar, Amplitude, Google Console, Firebase

---

### Fun Fact:
I’m a big fan of optimizing code for speed and performance! There’s nothing more satisfying than shaving off those precious milliseconds and making websites run faster. ⚡

---

Looking forward to hearing from you! Let's build something awesome together! 🚀

# Project Setup Guide

Follow the steps below to set up the project on your local environment:

## 1. Install Python
If Python is not already installed, download and install it from [python.org](https://www.python.org/).

## 2. Install Virtual Environment
Install the virtual environment package using the following commands:

**Windows:**
```bash
pip install virtualenv
macOS and Linux:

```bash
sudo apt install python3-virtualenv
3. Set Up Virtual Environment
Navigate to the project directory and set up a virtual environment:

```bash
virtualenv venv
4. Activate Virtual Environment
Activate the virtual environment using the appropriate command for your OS:

Windows:

```bash
venv\Scripts\activate
macOS and Linux:

```bash
source venv/bin/activate
5. Install Dependencies
Install the required dependencies from the provided requirements_local.txt file:

bash
pip install -r requirements_local.txt
6. Configure Environment Variables
Edit the .env file in the project directory with the following configurations:

DEBUG=True
Set TIME_ZONE to your local time zone.
For local setups, set MYSQL_DB=False. If you prefer to use MySQL (not recommended for local servers):
Set MYSQL_DB=True
Configure DB_NAME, DB_USER, and DB_PASSWORD.
Set WHITENOISE_CONFIG=False.
7. Make Migrations
Run the following commands to create migrations:

Windows:

bash
Copy code
py manage.py makemigrations
macOS and Linux:

```bash
python3 manage.py makemigrations
8. Apply Migrations
Apply the migrations to the database:

Windows:

bash
py manage.py migrate
macOS and Linux:

bash
Copy code
python3 manage.py migrate
9. Create a Superuser
Create a superuser account for accessing the Django admin panel:

Windows:

bash
py manage.py createsuperuser
macOS and Linux:

bash
python3 manage.py createsuperuser
Provide the username, email, and password when prompted.

10. Start the Development Server
Run the Django development server using the following command:

Windows:

bash
py manage.py runserver
macOS and Linux:

bash
python3 manage.py runserver
You are now ready to access the application locally at http://127.0.0.1:8000/.
