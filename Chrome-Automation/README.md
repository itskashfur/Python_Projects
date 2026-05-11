<h1 align="center">Chrome Automation Tool</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Chrome-4285F4?style=for-the-badge&logo=Google-Chrome&logoColor=white" alt="Chrome">
</p>

<hr>

<h2>📌 Overview</h2>
<p>
  This project is a simple yet effective Python script designed to automate the process of opening multiple pre-defined URLs in the <strong>Google Chrome</strong> browser. It leverages the built-in <code>webbrowser</code> module to interact with the system's browser application.
</p>

<hr>

<h2>🚀 Features</h2>
<ul>
  <li><strong>Multi-URL Support:</strong> Define an array of links to open them sequentially.</li>
  <li><strong>Browser Path Customization:</strong> Points specifically to the Chrome executable for reliable launching.</li>
  <li><strong>Console Logging:</strong> Prints the status of each URL being opened to the terminal.</li>
</ul>

<hr>

<h2>🛠️ Prerequisites</h2>
<p>Ensure you have the following installed on your system:</p>
<ul>
  <li><strong>Python 3.x</strong></li>
  <li><strong>Google Chrome</strong> (installed at the default Windows path: <code>C:/Program Files (x86)/Google/Chrome/Application/chrome.exe</code>)</li>
</ul>

<hr>

<h2>💻 Usage</h2>
<ol>
  <li>Clone the repository:
    <pre><code>git clone https://github.com/itskashfur/Python_Projects.git</code></pre>
  </li>
  <li>Navigate to the project directory:
    <pre><code>cd Chrome-Automation</code></pre>
  </li>
  <li>Run the script:
    <pre><code>python chrome-automation.py</code></pre>
  </li>
</ol>

<hr>

<h2>📄 Code Structure</h2>
<p>
  The main logic is contained within the <code>webauto()</code> function:
</p>
<ul>
  <li><code>chrome_path</code>: Defines the local directory for the Chrome application.</li>
  <li><code>URLS</code>: A tuple containing the list of websites to be opened.</li>
  <li><code>wb.get(chrome_path).open(url)</code>: The core command that triggers the browser.</li>
</ul>

<hr>

<p align="center">
  <i>❤️ Created by <a href="https://github.com/itskashfur">Kashfur Rahman</a></i>
</p>
