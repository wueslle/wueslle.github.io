Professional AML Data Portfolio — Wueslle Thibes

This repository contains the source code for my professional portfolio, designed with a modern, tech-minimalist aesthetic tailored for the Fintech and Compliance industry. It is built to showcase data infrastructure, automated pipelines, and analytical investigations.

Live Version: wueslle.com (or yourusername.github.io)

👤 About Me

I build the data infrastructure that protects global financial systems. Currently at EBANX, I specialize in the intersection of Data Analysis and Compliance, focusing on Anti-Money Laundering (AML) and Transaction Monitoring across the LATAM market.

My expertise lies in transforming complex regulatory requirements into scalable automated pipelines. I leverage Python (Pandas/Statsmodels) and GCP/BigQuery to detect high-risk patterns and optimize financial integrity workflows.

Core Stack: SQL, Python (ETL & Statistical Modeling), GCP, BigQuery, Selenium, BeautifulSoup.

Domain: AML/CFT, RegTech, Transaction Monitoring, Sanctions.

🚀 Features

Bilingual Support: Fully translated between English (EN) and Portuguese (PT) with a single toggle.

Dark/Light Mode: Adaptive theme toggling to suit professional environments.

Responsive Design: Optimized for mobile, tablet, and desktop viewing.

Interactive Embeds: Built-in support for showcasing live Looker or Tableau dashboards.

Minimalist Aesthetic: Clean, high-performance UI built with Tailwind CSS.

🛠️ Built With

HTML5 & CSS3

Tailwind CSS (Utility-first styling)

Lucide Icons (Clean vector icons)

JavaScript (ES6) (Data-driven rendering engine)

📦 Deployment Guide

GitHub Pages

This site is hosted for free using GitHub Pages. To deploy your own version:

Upload index.html to a repository named yourusername.github.io.

Go to Settings > Pages and enable deployment from the main branch.

Custom Domain (Namecheap)

To point your Namecheap domain (wueslle.com) to this portfolio:

In GitHub Settings, add wueslle.com to the Custom Domain field.

In Namecheap Advanced DNS, add the following Host Records:

A Record: Host @ | Value 185.199.108.153

A Record: Host @ | Value 185.199.109.153

A Record: Host @ | Value 185.199.110.153

A Record: Host @ | Value 185.199.111.153

CNAME Record: Host www | Value yourusername.github.io

⚙️ How to Update Content

The website is entirely data-driven. You do not need to modify the structural HTML or CSS to update your information. Simply edit the DATA object inside the <script> tag at the bottom of index.html.

const DATA = {
    en: {
        profile: { ... },
        bio: [ ... ],
        projects: [ ... ]
    },
    pt: {
        profile: { ... },
        bio: [ ... ],
        projects: [ ... ]
    }
};


Developed by Wueslle Thibes
