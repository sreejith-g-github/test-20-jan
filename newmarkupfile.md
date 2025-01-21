# Creating a Virtual Machine in VMware Workstation

This document outlines the steps for creating a new virtual machine in VMware Workstation.

**Prerequisites:**

* **VMware Workstation:** Installed and running on your host machine.
* **Operating System ISO:** An ISO image of the desired operating system (e.g., Windows 10, Ubuntu Server).

**Steps:**

1. **Open VMware Workstation:** Launch the VMware Workstation application.

2. **Create a New Virtual Machine:**
   - Click **"File"** -> **"New Virtual Machine"**.
   - Select **"Typical (recommended)"** and click **"Next"**.

3. **Installer Disc Image:**
   - Select **"Installer disc image file (iso)"** and click **"Next"**.
   - Browse to and select the path to your operating system ISO image.
   - Click **"Next"**.

4. **License Agreement:**
   - Review the license agreement and click **"Next"**.

5. **Customization Options:**
   - **(Optional)** Customize the virtual machine name and location. 
   - Click **"Next"**.

6. **Disk Space:**
   - Specify the disk space allocation for the virtual machine.
     - You can choose to create a single file or multiple files.
   - Click **"Next"**.

7. **Customize Hardware:**
   - **(Optional)** Customize the hardware settings:
      - **Processor:** Adjust the number of cores and threads.
      - **Memory:** Allocate RAM to the virtual machine.
      - **Network:** Configure network settings (e.g., bridged, NAT, host-only).
      - **Hard Disk:** Modify disk size, type, and I/O.
      - **CD/DVD:** Select the ISO image or connect a physical drive.
   - Click **"Next"** and then **"Finish"**.

8. **Power On the Virtual Machine:**
   - The virtual machine will power on automatically.
   - Follow the on-screen instructions to install the operating system.

**Post-Installation:**

* **Install VMware Tools:** After installing the guest operating system, install VMware Tools within the guest OS for improved functionality (e.g., shared folders, drag-and-drop).

**Note:**

* The specific steps and options may vary slightly depending on your VMware Workstation version and the chosen operating system.
* Refer to the VMware Workstation documentation for detailed information and advanced configuration options.

This guide provides a basic framework for creating a virtual machine in VMware Workstation. You can adjust the settings to suit your specific needs and requirements.

**Additional Tips:**

* **Snapshotting:** Create snapshots of your virtual machine at different stages to easily revert to a previous working state.
* **Cloning:** Clone existing virtual machines to quickly create identical copies.
* **Resource Management:** Monitor and adjust resource allocation (CPU, memory) to optimize performance.

This document is for informational purposes only and should not be considered professional advice.