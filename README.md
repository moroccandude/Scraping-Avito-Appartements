<h1>🏡 Scraping-Avito-Appartements</h1>
<p>Explore web scraping techniques for collecting property data from real estate classifieds on Avito.</p>

<h2>🎯 Project Goals</h2>
<p>The primary goal of this project is educational, aimed at helping users gain familiarity with Python and popular frameworks like Pandas and Selenium.</p>

<h2>🛡 GDPR Compliance</h2>
<p>This project complies with GDPR (Règlement Général sur la Protection des Données) by utilizing ethical scraping practices and respecting user privacy. No personal information is collected.</p>

<h2>⚙️ Prerequisites and Setup</h2>
<p>To run this project, ensure the following technical requirements are met:</p>
<ul>
  <li><b>Python:</b> 3.13.0</li>
  <li><b>Required Libraries:</b> Selenium, Pandas, Numpy, and Jupyter</li>
</ul>

<h3>📥 Installation</h3>
<p>Install the required packages using the following command:</p>

<pre>
<code>pip install jupyter selenium pandas numpy</code>
</pre>

<h3>🔧 Project Setup</h3>
<ol>
  <li>Clone the repository:</li>
  <pre><code>git clone https://github.com/your-username/Scraping_Avito.git</code></pre>

  <li>Navigate to the project directory:</li>
  <pre><code>cd Scraping_Avito</code></pre>

  <li>Install the dependencies as outlined above.</li>
</ol>

<h2>🚨 Error Handling and Logging</h2>
<p>The project includes specific error handling for robust execution:</p>
<ul>
  <li><b>TimeoutException:</b> Raised when <code>WebDriverWait</code> cannot find an element within the specified time.</li>
  <li><b>NoSuchElementException:</b> Raised if an element cannot be located, returning "NON SPÉCIFIÉ."</li>
  <li><b>ElementClickInterceptedException:</b> Raised if a button is intercepted and cannot be clicked.</li>
</ul>
<p>These exceptions ensure the program runs smoothly, with each handled appropriately to enhance stability.</p>

<h2>⚡ Optimization Strategies</h2>
<p>Two scraping approaches are provided:</p>
<ul>
  <li><b>User-Agent Simulation:</b> Mimics natural user behavior for stealthier scraping at a slower pace.</li>
  <li><b>Fast Data Collection:</b> Optimized for speed to collect data quickly, though with an increased chance of detection.</li>
</ul>

<h2>📚 Resources</h2>
<p>For more in-depth information, consult the <a href="https://www.selenium.dev/documentation/">Selenium documentation</a>.</p>

<h2>📝 Licence</h2>
<p>I reached out to the HR Business Partner at Avito regarding permissions but have not yet received a response.</p>

<h2>🏁 Conclusion</h2>
<p>This project complies with GDPR regulations and is strictly for educational use only, with no support for malicious purposes.</p>
