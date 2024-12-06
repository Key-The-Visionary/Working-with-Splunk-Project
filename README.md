# Working with Splunk Basics Tutorial

<div class="container">
    <h2>Introduction to Splunk</h2>
    <p>Splunk is a powerful platform for searching, analyzing, and visualizing machine-generated big data. It helps in monitoring, searching, and analyzing machine-generated data through a web interface.</p>

  <h2>Step 1: Setting Up Splunk</h2>
    <p>To get started with Splunk, you need to install it on your local machine or use the Splunk Cloud. Follow these steps:</p>
    <ul>
        <li>Download Splunk from the official <a href="https://www.splunk.com/en_us/download.html" target="_blank">Splunk website</a>.</li>
        <li>Install Splunk using the provided installer for your operating system.</li>
        <li>After installation, open your browser and visit <strong>http://localhost:8000</strong> to access the Splunk web interface.</li>
        <li>Log in using the default credentials (username: admin, password: changeme).</li>
    </ul>

  <div class="note">
        <strong>Note:</strong> Change the default password after your first login for security reasons.
    </div>
<img src="https://github.com/user-attachments/assets/e82787ba-c3f8-4f67-b356-34f00c0828ff" width="500" height="300" />
<img src="https://github.com/user-attachments/assets/29900b57-27cd-41ae-9dba-07fc706ea696" width="500" height="300" />
<img src="https://github.com/user-attachments/assets/b78eea4f-e476-4480-b609-9adb3aa39c9f" width="500" height="300" />
<img src="https://github.com/user-attachments/assets/b8bdb88e-5b72-4f99-a6eb-09d59fdcf190" width="500" height="300" />
<img src="https://github.com/user-attachments/assets/9be6e135-23cf-4c0c-b167-f9ae0a8514d4" width="500" height="300" />






--------------------------------------------------------------------------------------------
  <h2>Step 2: Uploading Data to Splunk</h2>
    <p>To analyze your logs and data, you'll need to upload them into Splunk. You can upload data in the following ways:</p>
    <ul>
        <li>Click on <strong>Settings</strong> > <strong>Data Inputs</strong>.</li>
        <li>Choose the type of data you want to upload (e.g., files, directories, or HTTP event collectors).</li>
        <li>Follow the prompts to configure your data input settings and upload your data to Splunk.</li>
    </ul>

<img src="https://github.com/user-attachments/assets/e6363ad9-2a62-4e97-8df7-7c1768ec9347" width="500" height="300" />

<img src="https://github.com/user-attachments/assets/344caa8d-ed38-410f-85d9-a9cf35964190" width="500" height="300" />

---------------------------------------------------------------------------------------------------------------------------


  <h2>Step 3: Performing Basic Searches</h2>
    <p>Once your data is uploaded, you can start searching for specific logs or information. Use the search bar at the top of the Splunk interface to run queries.</p>

  <p>Here’s an example search query below:</p>
    
  <img src="https://github.com/user-attachments/assets/4aa78558-226c-42d7-b1e0-9702d6dd39ec" width="500" height="300" />







  ------------------------------------------------------------------------------------------------------------------------------

  <h2>Step 4: Splunk Query Language (SPL)</h2>
    <p>Splunk uses a powerful language called SPL (Search Processing Language) to query and manipulate data. Below are some basic SPL commands:</p>
    <ul>
        <li><strong>index=</strong> Specifies the index to search in.</li>
        <li><strong>sourcetype=</strong> Defines the type of log you are looking for.</li>
        <li><strong>stats</strong> Aggregates data. Example: <code>stats count by source</code> shows a count of events grouped by their source.</li>
    </ul>

---------------------------------------------------------------------------------------------------------------------------------------------
  
  <h2>Step 5: Creating Visualizations</h2>
    <p>Splunk allows you to create various visualizations, such as bar charts, pie charts, and line graphs. After running your query, click on the "Visualization" tab to view your results graphically.</p>

  <img src="https://github.com/user-attachments/assets/9d1a086b-81f6-4ef3-aac7-19e23ee3ad53" width="500" height="300" />

   <img src="https://github.com/user-attachments/assets/6f838c45-6d78-4d87-bfb3-83e98236e76f" width="500" height="300" />


   

  --------------------------------------------------------------------------------------------------------------------------------------------

   <h2>Step 6: Creating Alerts</h2>
    <p>To monitor specific conditions, you can create alerts in Splunk. For example, if you want to be notified of a particular error, you can create an alert with the following steps:</p>
    <ul>
        <li>Run your search query.</li>
        <li>Click on the <strong>Save As</strong> button and select <strong>Alert</strong>.</li>
        <li>Set up the conditions for when the alert should trigger (e.g., when a specific error occurs).</li>
        <li>Choose how you want to be notified (e.g., email, script, etc.).</li>
    </ul>


  <img src="https://github.com/user-attachments/assets/4838f622-0dbc-4229-9aba-34132c2e460c" width="500" height="300" />


-------------------------------------------------------------------------------------------------------------------------------------
  <h2>Conclusion</h2>
    <p>Splunk is an incredibly powerful tool that can help you monitor, search, and analyze machine data in real-time. With its extensive search capabilities and flexible dashboarding options, you can gain insights into your infrastructure, applications, and security posture.</p>
    <p>For more advanced tutorials and use cases, visit the official <a href="https://www.splunk.com" target="_blank">Splunk documentation</a>.</p>
</div>

</body>
</html>
