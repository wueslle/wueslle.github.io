Professional AML Data Portfolio

This repository contains the source code for my professional portfolio, designed with a modern, tech-minimalist aesthetic tailored for the Fintech and Compliance industry.

Live Version: wueslle.com (or your-username.github.io)

👤 About Me

I build the data infrastructure that secures global financial systems. Currently at EBANX, I specialize in the convergence of Data Analysis and Compliance, focusing on Anti-Money Laundering (AML) and Transaction Monitoring across the LATAM market.

Core Stack: SQL, Python (ETL & Statistical Modeling), GCP, BigQuery, Selenium, BeautifulSoup.

Domain: AML/CFT, RegTech, Transaction Monitoring, Sanctions.

🚀 Features

Bilingual Support: Fully translated between English (EN) and Portuguese (PT).

Dark/Light Mode: Seamless theme toggling to suit user preference.

Responsive Design: Optimized for mobile, tablet, and desktop viewing.

Interactive Embeds: Ability to showcase live Looker or Tableau dashboards directly within project cards.

Minimalist Aesthetic: Clean, high-performance UI built with Tailwind CSS.

🛠️ Built With

HTML5 & CSS3

Tailwind CSS (Utility-first styling)

Lucide Icons (Vector icons)

JavaScript (ES6) (Dynamic rendering engine)

📦 Deployment Guide

GitHub Pages

This site is hosted for free using GitHub Pages. To deploy your own version:

Upload index.html to a repository named username.github.io.

Go to Settings > Pages and enable deployment from the main branch.

Custom Domain (Namecheap)

To point your Namecheap domain (wueslle.com) to this portfolio:

In GitHub Settings, add wueslle.com to the Custom Domain field.

In Namecheap Advanced DNS:

Add 4 A Records pointing to GitHub IPs: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153.

Add a CNAME Record with Host www and Value yourusername.github.io.

⚙️ How to Update

The website is data-driven. You do not need to edit complex HTML/CSS to change your content. Simply edit the CONFIG object at the bottom of index.html:

const DATA = {
    en: {
        profile: { ... },
        kpis: [ ... ],
        bio: [ ... ],
        projects: [ ... ]
    },
    pt: { ... }
};


Developed by Wueslle Thibes
