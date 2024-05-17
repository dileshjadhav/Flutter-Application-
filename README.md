# News_APP

About

This app is a news app which fetched News From NewsAPI.org.

TO RUN THIS FOLLOWING STEPS NEED TO FOLLOW:


# Step 1: Ensure Flutter is Up-to-Date
First, make sure your Flutter SDK is up-to-date. Open a terminal and run:

flutter upgrade

# Step 2: Enable Web and Windows Support
Enable web and Windows support in your Flutter project by running the following commands:

Enable Web Support

flutter config --enable-web

Enable Windows Support

flutter config --enable-windows-desktop

# Step 3: Generate Platform-Specific Files
Generate the necessary files for web and Windows platforms. Navigate to your project directory and run:

cd D:\downloads\Flutter_NewsApp-master\Flutter_NewsApp-master
flutter create .

# Step 4: Run the Project on the Desired Platform
After enabling and generating the necessary files, you should be able to run your Flutter project on the desired platform.

Run on Chrome (Web)
flutter run -d chrome

Run on Windows (Desktop)
flutter run -d windows

# Step 5: Resolve Other Potential Issues
If you still encounter issues, ensure that your project dependencies are up-to-date and properly configured.

Update Dependencies
Run:
flutter pub get
