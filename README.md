# Meetup Photos
Download entire photo album from meetup.com to local folder

See https://belablotski.blogspot.com/2018/03/download-photo-albums-from-meetupcom_46.html for usage details.

Forked from belablotski's repo. Note that the URL is hardcoded to only focus on **Anak IT Brunei's** albums and no one else's. To change it, open the `.sln` file in Visual Studio and change the group URL. This requires **.NET Framework 4.6** so be sure to install that before opening the `.sln` file.

## Usage

1. Clone the repo
2. Navigate to the cloned repo
3. Then run `MeetupImages.exe {Album ID} {Output Directory}` in Command Prompt/PowerShell

E.g. `MeetupImages.exe 29029706 .\capture-the-flag-prize-presentation-ceremony\`