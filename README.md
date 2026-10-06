# Flavorful Feast

Create a complete, modern and professional restaurant website using React.js.

Main Requirements

Use React.js with simple, clean and beginner-friendly code.

Make the website fully mobile responsive for mobile, tablet and desktop.

Use HTML5, CSS3, JavaScript and React.

Create a proper index.html file so the project can be deployed directly on Netlify.

Use React Router for navigation between pages.

The website should have a professional restaurant/food theme.

Use attractive food images, cards, buttons, icons and responsive layouts.

Keep the code simple enough for a college student to understand and modify.

Do not use unnecessary complicated libraries.

Make sure there are no broken links or console errors.

Restaurant Website Pages

Create these main pages:

Home

About Us

Services

Branches

Contact Us

Every section should have its own proper page/route.

Home Page

Include:

Attractive restaurant hero/banner section

Restaurant name and tagline

"Order Now" button

"Book a Table" button

Featured dishes

Popular menu items

Why Choose Us section

Restaurant highlights

Customer reviews/testimonials

Call-to-action section

Footer

Example tagline:
"Delicious Food, Memorable Moments."

About Us Page

Include:

Restaurant introduction

Our story

Mission and vision

Restaurant values

Chef/Team section

Quality and hygiene information

Attractive food/restaurant images

Services Page

Create service cards for:

Dine-In

Takeaway

Home Delivery

Online Ordering

Table Reservation

Catering

Party & Event Services

Each service should have:

Icon

Title

Short description

Learn More button

Branches Page

Display multiple restaurant branches using responsive cards.

Each branch card should contain:

Branch name

Address

City

Phone number

Opening hours

Google Maps button

View Details button

Create sample branches such as:

Pune

Mumbai

Kolhapur

Sangli

Make the branch information easy to edit later.

Contact Us Page

Include:

Contact form

Name

Email

Phone

Subject

Message

Submit button

Restaurant phone number

Email address

Address

Opening hours

Social media icons

Google Maps section

The contact form should have basic validation.

Navigation Bar

Create a responsive navbar with:

Restaurant logo/name

Home

About

Services

Branches

Contact Us

Order Now button

On mobile:

Show a hamburger menu

Menu should open and close smoothly.

Footer

Create a professional footer containing:

Restaurant name

Short description

Quick links

Services

Branch locations

Contact information

Social media icons

Copyright

Design

Use a modern restaurant design:

Premium but simple appearance

Warm food/restaurant-inspired colors

Clean typography

Rounded cards

Smooth hover effects

Subtle animations

Good spacing

High-quality food images

Responsive grid layouts

Do not make the design overly complicated.

React Project Structure

Use a structure similar to:

src/
├── components/
│ ├── Navbar.jsx
│ ├── Footer.jsx
│ ├── Hero.jsx
│ ├── FoodCard.jsx
│ └── ServiceCard.jsx
│
├── pages/
│ ├── Home.jsx
│ ├── About.jsx
│ ├── Services.jsx
│ ├── Branches.jsx
│ └── Contact.jsx
│
├── App.jsx
├── main.jsx
└── index.css

Also create:

public/
└── images/

index.html
package.json

Routing

Use React Router and create these routes:

/
/about
/services
/branches
/contact

Make sure navigation works correctly without page reload problems.

Netlify Deployment

Configure the project so it can be deployed easily on Netlify.

Include:

Correct index.html

package.json

React build configuration

Netlify SPA redirect configuration if required

Make sure React Router routes work after deployment.

If required, create:

public/_redirects

with:

/* /index.html 200

Important

Generate the complete working project, not just an explanation.

Provide all required files and their complete code.

The final website should:

Run using npm install

Start using npm run dev

Build using npm run build

Deploy successfully to Netlify

Work on mobile, tablet and desktop

Have working navigation between all pages

Have a professional restaurant UI

Have editable sample restaurant data

Use reusable React components

Have clean and readable code

Use a fictional restaurant name such as "Spice Garden Restaurant", but structure the code so I can easily change the restaurant name, images, branches, menu and contact information later.

At the end, provide simple step-by-step instructions for:

Creating the project

Installing dependencies

Running it locally

Building the project

Uploading/deploying it to Netlify

Connecting the GitHub repository to Netlify

This project was built with [Lovable](https://lovable.dev).

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/ca80e595-6b52-4403-8e03-d39f2402d319).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
