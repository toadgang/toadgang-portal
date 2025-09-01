Toadgang Community Portal
This repository contains the open-source code for the Toadgang Community Portal, a website dedicated to providing stats, charts, and information about the Toby, Taboshi, and Patience tokens on the Base network.

The live, decentralized version of this site is hosted on IPFS.

🚀 Running the Portal Locally
You can run your own version of this portal on your local computer. This is useful for testing changes or for developers who want to build on top of this project.

Prerequisites
A local web server environment like XAMPP (for Windows/Mac/Linux) or MAMP (for Mac/Windows). This is required to run the PHP script.

A free API key from Moralis.

Setup Instructions
Download the Code:

Click the green "<> Code" button on this GitHub page and select "Download ZIP".

Unzip the folder to your computer.

Set up Local Server:

Install and run XAMPP or MAMP.

Move the entire project folder you just unzipped into the htdocs folder of your XAMPP/MAMP installation.

Configure Your API Key:

Open the api.php file in a code editor like Visual Studio Code.

Find the line that says $apiKey = '...';

Replace the existing key with your own secret API key from Moralis.

Run the Site:

Make sure your Apache server is running in XAMPP/MAMP.

Open your web browser and navigate to http://localhost/your-folder-name/ (e.g., http://localhost/toadgang-portal-main/).

The website should now be running on your local machine, pulling live data using your own API key.