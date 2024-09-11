# **Creating a Linux VM on Azure**

## Prerequisites

Before we begin, let’s make sure you have everything you need:

1. **Microsoft Azure Account:** To create a virtual machine (VM) on Azure, you’ll need an Azure account. If you don’t have one, you can sign up for free at [azure.microsoft.com](https://azure.microsoft.com).

2. **Basic Computer Knowledge:** No need to be a computer genius! As long as you know how to use a browser and can follow steps, you’ll be able to create a Linux VM.

3. **Internet Connection:** Since Azure is a cloud service, you’ll need a stable internet connection to access it.

## What is a Virtual Machine (VM)?

A **virtual machine (VM)** is like having a second computer inside your computer! But instead of using physical parts (like a CPU and RAM), it runs using software. A VM allows you to run a different operating system (like Linux) without changing your computer’s own operating system. In this case, we will create a **Linux** VM on **Azure**, which is a cloud platform.

## Why Use a Linux VM on Azure?

Using a Linux VM on Azure can be useful for many reasons:

- **Learning:** You can practice using Linux without installing it on your computer.
- **Developing Applications:** Developers can write and test programs on a Linux environment.
- **Hosting Websites:** Linux is great for running websites or servers.

Now, let’s move on to how to create a Linux VM step by step.

## How to Create a Linux VM on Azure: Step by Step

Here’s a super-simple guide to help you create your very own Linux VM:

### Step 1: Sign In to the Azure Portal

1. Go to [Azure Portal](https://portal.azure.com) and log in with your Microsoft account. If you don’t have an account, create one (don’t worry, it’s free for basic use!).

2. Once logged in, you’ll see the **Azure dashboard**.

### Step 2: Create a Virtual Machine

1. On the dashboard, click the **"Create a resource"** button (it’s usually on the left side or at the top).

2. In the search bar, type "**Virtual Machine**" and select **"Virtual Machine"** from the dropdown.

3. Now, you’ll see a **"Create a virtual machine"** page. Click the **"Create"** button.

### Step 3: Set Up Basic Settings

1. **Subscription:** Choose your Azure subscription. If you’re using a free trial, this will be selected automatically.

2. **Resource Group:** Think of a resource group as a folder where you keep all related stuff. If you don’t have one, click **"Create new"** and give it a name, like "MyVMGroup".

3. **VM Name:** Give your virtual machine a name, like "MyLinuxVM".

4. **Region:** Choose a region close to your location. For example, if you're in India, you might pick "Central India". This just helps with speed and availability.

5. **Image:** This is where you select the operating system. Choose **"Ubuntu 20.04 LTS"** (this is a popular and beginner-friendly version of Linux).

6. **Size:** This is like deciding how powerful your virtual machine should be. Choose the **Standard_B1s** size, which is enough for learning and small projects (and it's cheap!).

### Step 4: Set the Login Details

1. **Authentication Type:** Choose **"Password"** so you can log in with a username and password.

2. **Username:** Pick a username, like "student" or your own name.

3. **Password:** Create a strong password (you’ll need this to log in to your VM later). Make sure to note it down somewhere!

### Step 5: Configure Networking

1. Scroll down to the **Networking** section and leave most options as they are. This tells Azure how your VM will connect to the internet.

2. Make sure **"Allow selected ports"** is set to **"SSH (22)"**. SSH lets you connect to your VM from your computer.

### Step 6: Review and Create

1. Click **"Review + Create"** at the bottom of the page. This will show a summary of your VM settings.

2. If everything looks good, click **"Create"**. Azure will take a few minutes to set up your VM.

### Step 7: Connect to Your Linux VM

1. Once your VM is created, you’ll see a **"Go to resource"** button. Click it.

2. On the next page, you’ll see a public IP address for your VM. Copy this IP address.

3. Now, open a terminal (if you're on Windows, you can use **PowerShell** or an SSH client like **PuTTY**).

4. In the terminal, type:

   ```bash
   ssh <your-username>@<your-vm-ip-address>
   ```
   Replace `<your-username>` with the username you created earlier and `<your-vm-ip-address>` with the IP address you just copied.

5. Enter your password when prompted, and you’ll be connected to your Linux VM!
 
## Use of Linux VM on Azure

Now that your Linux VM is up and running, what can you do with it? Here are a few cool things:

- Learn Linux Commands: Practice common Linux commands like ls, cd, and echo. If you’re new to Linux, this is a great way to get familiar with the operating system.

- Host a Website: You can install web servers like Apache or Nginx and host your own website!

- Run Code: If you’re learning programming languages like Python or Java, you can write and run code directly on your Linux VM.

- Experiment with Software: Want to try out different software? Your VM is the perfect place to experiment without affecting your main computer.

## Conclusion

Creating a Linux VM on Azure is a fantastic way to explore Linux, develop projects, or even host websites. Plus, since it’s all in the cloud, you don’t need to worry about messing up your computer! With just a few simple steps, you can have your own powerful virtual machine ready to go.

---

**Creator: Shashank Naik | Cloud Computing Intern, WEBXELA**

- [LinkedIn](https://www.linkedin.com/in/shashank-naik09061319)
- [GitHub](https://github.com/Shashank693)
---