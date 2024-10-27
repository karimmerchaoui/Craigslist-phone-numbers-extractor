<div align='center'>

![Craigslist_Phone_Numbers_extractor (4)](https://github.com/user-attachments/assets/38e8fc66-b9db-4c72-b700-a6f9d73b9fe7)

</div>

# Overview
 This Python-based web scraping tool solves the problem of manually extracting phone numbers from Craigslist postings. It automates data collection by interacting with listings, gathering key details (title, description, post date, phone numbers), and saving them into Excel files for easy access and analysis.

## Who Would Benefit from This Tool:

<ul>
    <li><strong>Employers</strong>: Quickly identify potential job candidates by extracting contact information from listings.</li>
    <li><strong>Recruiters</strong>: Efficiently gather data on individuals seeking employment to streamline the hiring process.</li>
    <li><strong>Small Business Owners</strong>: Find skilled individuals advertising their services or looking for job opportunities.</li>
    <li><strong>Real Estate Agents</strong>: Identify and reach out to individuals who may be looking to fill roles within the industry.</li>
    <li><strong>Hiring Managers</strong>: Compile a list of job seekers in specific industries or locations for targeted outreach.</li>
    <li><strong>Networking Professionals</strong>: Connect with potential candidates actively seeking job opportunities.</li>
</ul>



<div align='center'>
 


  <img src="https://github.com/user-attachments/assets/669726fd-c69e-4083-ab34-bdeaaf3cc979" width="80%" alt="Overview Image">

</div>


# Technologies Used

- **Python:** The programming language for building the application.
- **Tkinter:** For the graphical user interface.
- **Selenium:** For web scraping and browser automation.
- **Beautiful Soup:** For parsing HTML and XML documents.
- **Requests:** For making HTTP requests to retrieve webpage content.
- **Pandas:** For data manipulation and saving to Excel files.
- **geopy:** For geocoding city and state input into latitude and longitude.
- **fake_useragent:** To randomize user agents during scraping.
- **NordVPN:** Used for connecting to a VPN for anonymous browsing.

# Features
<ul>
<li>Automates phone number extraction from Craigslist posts.</li>
<li>Saves data (title, description, phone number, post date) to Excel for analysis.</li>
<li>Uses Selenium for automated web interaction.</li>
<li>Supports VPN handling to bypass geographical restrictions.</li>
<li>Displays progress with a user-friendly GUI built with Tkinter.</li>
</ul>

# Installation
<ul>
<li>Automates phone number extraction from Craigslist posts.</li>
<li>Saves data (title, description, phone number, post date) to Excel for analysis.</li>
<li>Uses Selenium for automated web interaction.</li>
<li>Supports VPN handling to bypass geographical restrictions.</li>
<li>Displays progress with a user-friendly GUI built with Tkinter.</li>
</ul>


## Prerequesite

<ul>
<li>Python 3.x</li>
<li>pip (Python package manager)</li>
<li>Google Chrome browser and <a href="https://chromedriver.chromium.org/downloads">ChromeDriver</a></li>
</ul>

## Steps
<ul>
  <li>Clone the repository:
    <pre><code>
git clone https://github.com/karimmerchaoui/Craigslist-phone-numbers-extractor/edit/main/README.md
cd Craigslist-phone-numbers-extractor
</code></pre>
  </li>
  <li>Install required dependencies:
    <pre><code>
pip install -r requirements.txt
</code></pre>
  </li>
</ul>



# Usage

<ol type="1">
    <li>Ensure your VPN is active (NordVPN recommended).</li>
    <li>Run the application:</li>
    <pre><code>python src/main.py</code></pre>
    <li>Enter the city, state, and search radius in the GUI.</li>
    <li>Click "Scrape" to begin extracting phone numbers from Craigslist postings.</li>
</ol>

# Output


<ul>
 The output of this application is an Excel file containing key details extracted from Craigslist postings. Each row represents a distinct job listing. 
 <br> <br>
    <li>The <strong>Title</strong> column provides the job title.</li>
    <li>The <strong>Description</strong> column contains detailed information about the poster's profile.</li>
    <li>The <strong>Phone Number</strong> column lists the contact information of the job poster, allowing employers to reach out directly to candidates.</li>
    <li>The <strong>Posted Date</strong> indicates when the listing was published.</li>
</ul>


<div align='center'>


  <img src="https://github.com/user-attachments/assets/7df584da-c4cb-4c1a-a9af-7b1c65faaa42" width="70%" alt="Overview Image">
</div>




