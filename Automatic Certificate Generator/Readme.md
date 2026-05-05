<div align="center">
  <h1>📜 Automatic Certificate Generator</h1>
  <p><i>Effortlessly generate personalized certificates in bulk using Python.</i></p>
</div>

<hr>

<h3>📖 Description</h3>
<p>
  This Python utility automates the process of creating individual certificates by mapping data from a <strong>CSV file</strong> onto a <strong>Certificate Template</strong>. 
  The script handles text positioning and batch processing, saving you hours of manual work.
</p>

<div style="background-color: #f6f8fa; padding: 15px; border-left: 5px solid #2188ff; border-radius: 5px;">
  <strong>📂 Output:</strong> All generated certificates are automatically saved to the <code>/pictures</code> folder within the script directory.
</div>

<h3>🚀 Installation</h3>
<p>Ensure you have <a href="https://www.python.org/downloads/">Python</a> installed on your system. Run the following commands to install the necessary dependencies:</p>

<pre style="background-color: #24292e; color: #e6edf3; padding: 16px; border-radius: 6px; overflow: auto;">
<code>pip install pandas
pip install pillow</code>
</pre>

<h3>🛠️ Project Structure</h3>
<table>
  <tr>
    <td><strong>File/Folder</strong></td>
    <td><strong>Description</strong></td>
  </tr>
  <tr>
    <td><code>main.py</code></td>
    <td>The core script to run the generator.</td>
  </tr>
  <tr>
    <td><code>list.csv</code></td>
    <td>The database containing names and details.</td>
  </tr>
  <tr>
    <td><code>template.png</code></td>
    <td>Your certificate background (JPG or PNG).</td>
  </tr>
  <tr>
    <td><code>/pictures/</code></td>
    <td>Automatic folder where results are stored.</td>
  </tr>
</table>

<h3>📝 How to Use</h3>
<ol>
  <li>Prepare your <code>list.csv</code> with a column for names.</li>
  <li>Ensure your certificate template is in the main folder.</li>
  <li>Run the script using <code>python main.py</code>.</li>
  <li>Collect your files from the <strong>pictures</strong> folder.</li>
</ol>

<hr>

<div align="center">
  <p>Maintained by <a href="https://github.com/itskashfur">itskashfur</a></p>
</div>
