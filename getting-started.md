# Getting Started with Archetype: Gojira X

This guide will help you install, activate, and configure Archetype: Gojira X so you can start playing in minutes.

## 1. System Requirements Check

Before installation, ensure your setup meets the minimum requirements:
* **OS:** macOS 11 (or higher) / Windows 10 (or higher)
* **RAM:** 8 GB or more
* **Hardware:** Electric guitar/bass, audio interface, and headphones/studio monitors.
* **Software:** Free **iLok License Manager** account.

---

## 2. Installation & Activation

### Step 1: Download the Installer
Go to the [Neural DSP Downloads page](https://neuraldsp.com) and download the installer for your operating system.

### Step 2: Run the Setup
1. Launch the installer and follow the on-screen prompts.
2. *(Optional)* Select custom plugin formats (VST3, AU, AAX) if you use a specific DAW. By default, all formats including the Standalone app will be installed.

### Step 3: Activate Your License
1. Launch the **Archetype Gojira X** standalone application.
2. Click **Try** (for a 14-day free trial) or **Activate** (if you purchased a license).
3. Log in with your **iLok** credentials when prompted to link the license to your machine.

---

## 3. First Launch & Audio Configuration

Launch the standalone version of the plugin to configure your audio routing.

> ⚠️ **IMPORTANT FOR macOS USERS:**  
> Upon the very first launch, macOS will ask for **Microphone Access**. You **must click "Allow"**. macOS categorizes all external audio interfaces as "Microphone" inputs. If you deny this, the plugin will receive no guitar signal.

### Step 4: Configure Settings
Click the **SETTINGS** button in the utility bar at the bottom of the interface to open the audio preferences. Match the parameters below:

| Parameter | Recommended Value | Why it matters |
| :--- | :--- | :--- |
| **Audio Device Type** | **CoreAudio** (macOS) / **ASIO** (Windows) | Ensures the lowest possible hardware latency. |
| **Audio Device** | Select your connected audio interface. | Routes the guitar sound into the software. |
| **Audio Input Channels** | Input channel where your guitar cable is plugged in. | Usually Input 1 or Input 2. |
| **Sample Rate** | **48000 Hz** | Standard high-quality audio processing rate. |
| **Audio Buffer Size** | **128 samples** or lower | Reduces delay between plucking a string and hearing the sound. |

Close the **Settings** window. Turn up your audio interface input gain, select a preset in the top manager, and you are ready to play!

