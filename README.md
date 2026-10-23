Digital Marketing Services

Business		: Digital Marketing Services
Location		: Manguzi, KwaZulu-Natal, South Africa
Owner / CEO		: Lucas Smanga Ndimande
WebSite Link 	: digitalmarkertingservices.rf.gd
Web developer	: Nzuzo Mkhize

1. Introduction
Digital Marketing Services is a local business in Manguzi that helps students, job seekers and community members with online applications and digital services. These include bursary and university applications, CV writing, PSIRA registrations, SARS and SASSA services, printing, tech support, graphic design and business registration. This document describes the business website: why it was built, who it is for, what it does and how it is maintained.

2. Background
The business has operated since the 2010s. Many people in the area struggle with online forms and government portals, or lack the devices and data to use them. Customers have mostly found the business by word of mouth and by visiting in person. The website extends this service online and presents it professionally.

3. The Need
Without a website, the business has these problems:
•	Potential customers cannot see what services are offered, or where and when the business is open.
•	There is no online presence for people who search for help with NSFAS, PSIRA or CV writing.
•	Customers must visit or phone just to ask what a service involves, which costs time and data.
•	The business looks less credible than competitors who have an online presence.
A website solves these problems by giving customers one place to see the services, check the opening hours, find the location and start a conversation immediately.
4. Purpose and Objectives
Purpose: To promote the business and make it easy for customers to contact it.
Objectives:
1.	Present all nine services clearly.
2.	Let a customer start a request in one tap, through WhatsApp.
3.	Show opening hours and whether the business is open right now.
4.	Help customers find the premises, using a map and directions.
5.	Work well on mobile phones, since most customers use them.
6.	Build trust through a clean, professional design.

5. Target Audience
•	Matric learners and students applying to universities, colleges, NSFAS and bursaries.
•	Unemployed and employed job seekers who need CVs and job applications.
•	Security officers needing PSIRA registration or renewal.
•	Residents needing help with SARS, SASSA or other government services.
•	Small business owners needing company registration, business plans, flyers or posters.
Most of these users browse on mobile phones with limited data, so the website is designed to load quickly and to be simple to use.

6. Services Offered
1.	Education Applications: university, college, and bursary applications, including NSFAS and Funza Lushaka.
2.	Job Search Support: job searching, online applications and interview preparation.
3.	Professional CV Writing: customised, ATS-friendly CVs and cover letters.
4.	PSIRA Registrations: applications, renewals and compliance services.
5.	Government Services: SARS tax registration, SASSA grant applications and others.
6.	Document Services: printing, scanning, email and document formatting.
7.	Tech Support: Windows installation, software setup and basic troubleshooting.
8.	Graphic Design: flyers, posters, invitations and promotional material.
9.	Business Services: CIPC company registration, business plans and entrepreneurial support.





7. Website Structure
The website is a single page made up of the following sections, in order:
1.	Hero section: logo, business name, tagline, and buttons for "Get In Touch" and "Our Services".
2.	About Us: a short description of the business and its strengths (fast service, affordable, professional, local experts).
3.	Our Services: nine service cards.
4.	How It Works: a three-step explanation of the process.
5.	Business Information: business details and operating hours, with a live open/closed indicator.
6.	Contact Us: phone/WhatsApp number, email, location, social media icons and an embedded map with directions.
7.	Footer: copyright and developer credit.
8.	Floating WhatsApp button: always visible in the corner of the screen.

8. Key Features and Why They Were Included
Feature	Purpose
Service cards that open WhatsApp	A customer taps a service and WhatsApp opens with a message such as "Hello, I am interested in PSIRA Registrations". This removes the need to type or explain from scratch.
Floating WhatsApp button	Lets customers reach the business from any part of the page.
How It Works section	Shows customers the process is simple, which reduces fear of "digital things".
Open/Closed indicator	Shows green when the business is open and red when closed, using South African time, so customers know whether they can come in.
Embedded map and Get Directions	Helps customers find the premises.
Typing-free contact	Customers on basic phones do not need to fill in forms.
Scroll animations and card effects	Give the site a modern, professional feel.
Confetti on WhatsApp tap	A small, friendly touch that makes the site memorable.
	


9. Design Decision: WhatsApp Instead of a Contact Form
The first version of the website had a contact form that saved messages in a MySQL database, with an admin page for reading them. This was later replaced with WhatsApp contact for these reasons:
•	Customers in the area already use WhatsApp daily, so it is the easiest channel for them.
•	The conversation starts immediately, and customers can send documents and photos in the same chat.
•	A form depends on a server script and email delivery, which are unreliable on free hosting and can fail without anyone noticing.
•	It removes the need to store customers' personal information in a database, which lowers security risk.
•	There is less to maintain.

10. Technology Used
•	HTML5: the structure of the page.
•	Tailwind CSS: layout and styling, loaded from a CDN.
•	Animate.css: the entrance animation of the hero text.
•	JavaScript: the scroll animations, card glow, confetti effect and open/closed indicator.
•	canvas-confetti: the confetti library.
•	Google Maps embed: the location map.
•	WhatsApp click-to-chat links (wa.me): the service buttons and the floating button.
•	InfinityFree: web hosting.

11. Design
The design uses a dark background with cyan and blue accents. Cyan highlights headings, buttons and icons, and green is used for WhatsApp and for the "open" status. Emoji icons mark each service. Cards lift and glow when touched or hovered, and sections fade in as the visitor scrolls. The text is white and grey on a dark background for readability.

12. Hosting and Deployment
1.	Log in to the InfinityFree dashboard.
2.	Open the File Manager (or use FTP).
3.	Open the htdocs folder and remove any old index.php.
4.	Upload index.html and logo.jpg.
5.	Visit the website address and test it.
Only two files are needed for the website to work. Old files from the first version (the form handler, database connection, admin pages and database backup) are no longer used and should not be uploaded, because some contain private details.


13. Testing Checklist
•	Every service card opens WhatsApp with the correct message.
•	The floating WhatsApp button works.
•	The open/closed indicator shows the correct state for the current time.
•	The map shows the right location and Get Directions opens Google Maps.
•	The page displays correctly on a phone, tablet and computer.
•	Phone, email and WhatsApp links work.
•	Images and the logo load.


14. Maintenance
•	Opening hours: update the visible list in Business Information and the times inside the script at the bottom of the page.
•	Services: edit the text of a service card, or copy a card to add a new one.
•	Contact details: update the phone number and email in the contact section and in the WhatsApp links.
•	Social media: replace the placeholder links with real page addresses once they exist.
•	Copyright year: update the footer each year.
•	Keep a backup copy of index.html before making changes.


15. Limitations and Risks
•	The open/closed indicator does not know about public holidays or temporary closures.
•	The design and effects depend on external services (Tailwind, the map and the confetti library), so some features will not load without internet.
•	Free hosting has limited speed and no guarantee of uptime.
•	The website uses a free web address, which is harder to remember and to find on Google than a custom domain.
•	There are no customer records, because contact happens in WhatsApp. Customer details are only kept in the owner's phone.
•	Social media links are not yet active.

16. Future Improvements
•	A custom domain such as a .co.za address.
•	Starting prices on each service.
•	Real photos of the premises and team in place of stock images.
•	A FAQ section (for example, documents needed for NSFAS).
•	Customer testimonials.
•	Active Facebook, Instagram and other social media links.
•	A public holiday list for the open/closed indicator.
•	Registering the site with Google so customers can find it when searching for services in Manguzi.

17. Conclusion
The website gives Digital Marketing Services a professional online presence and a simple way for customers to start a request. By using WhatsApp as the main contact channel, it suits how the community already communicates, keeps the system reliable on free hosting, and avoids the need to store customer data. It can grow over time as the business adds services, photos and social media pages.

