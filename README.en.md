# Personal Assistant
# Contact book dream_9_bot

Overview.

The dream_9_bot contact book is a simple command-line interface (CLI) application written in Python. It allows users to manage their personal address book, perform various operations on contacts, mark contacts with specific tags for easy search, sort files in the contact book, and even check the weather for a given city.

Features.

1. Add contacts: Easily add new contacts to your address book with information such as name, country, phone numbers, date of birth, email, and notes.
2. Search contacts: Search by different categories such as name, country, phone numbers, birthday, email, or notes.
3. Edit contacts: Change existing contact information, including name, country, phone numbers, birthday, email, or notes.
4. Delete contacts: Delete contacts by name or phone number.
5. Save and load: Save your address book to a file or load it from a file for easy storage.
6. View contacts: Displays all contacts in a table format, making it easy to view and manage your address book.
7. Weather information: Check the current weather for the specified city using the OpenWeatherMap API.
8. Greeting contacts: Check which contacts you need to greet this week.
​
Usage.

1. Installation: Make sure you have Python installed and install the necessary dependencies with:
   pip install rich, pip install requests, and pip install setuptools.
2. Run the program: Run the script by running the following command: python __main__.py
3. Commands: Use the following commands in dream_9_bot:
     'add': Add a new contact.
     'search': Search for contacts using the specified criteria.
     'edit': Edit existing contact information.
     'remove': Delete a contact.
     'save': Save the address book to a file.
     'load': Load the address book from a file.
     'congratulate': Check which of your contacts has a birthday coming up.
     'view': View all contacts in a table format.
     'weather': Get the weather for the specified city.
4. Exit: To exit the program, use the exit command.

​
Weather function

Overview.

The dream_9_bot contact book contains a weather function that allows you to check the weather for a specific city. Use the weather command followed by the city name, or you will be prompted to enter the city name when you execute the command.

Note: Make sure you have a valid API key for the weather function. Replace the api_key placeholder in the script with your valid API key: api_key = 'your_openweathermap_api_key'

Dependencies

Rich: Python library for rich text and beautiful formatting in the terminal.
​
Tagging function

Overview.

The tagging feature in dream_9_bot allows users to mark their contacts with specific tags for easy search and organization. Tags are a useful tool for categorizing contacts according to various criteria.

To use tags

1. Add tags to your contacts:
 Use the 'tag' command to add tags to your contacts.
 When you execute the command, the system will ask you for the name of the contact you want to add tags to.
 Then enter the tags, separated by spaces, that you want to assign to this contact.
     Here's an example of how to use it:
         Command: tag_search
         Enter the name of the contact: Olga
         Enter the tags (for example, friends family): friends family
​
2. Search by tag
 Use the 'tag_search' command to search for contacts by a specific tag.
 Enter a tag and the program will display a list of contacts that have that tag.
     An example of how to use it:
         Command: tad_search
         Enter a tag to search for (for example, family): family

3. Removing tags:
 Use the 'remove_tag' command to remove tags from a contact.
 Enter the name of the contact and then enter the tags you want to remove.
     Example of usage:
         Command: remove_tag
         Enter the name of the contact: Olga
         Enter the tags you want to delete (for example, family): family

Dependencies.

To use all the features of dream_9_bot, make sure you have the Rich library installed by running the following command:
pip install rich

File sorting function

Overview.

The File Sort function is designed to sort different types of files into folders according to their format within a user-defined directory. Below is a description of how files are sorted by their format:

Images
 JPEG: JPEG files are sorted into the images/JPEG folder.
 PNG: PNG files are sorted into the images/PNG folder.
 JPG: JPG files are sorted into the images/JPG folder.
 SVG: SVG files are sorted into the images/SVG folder.
​
Video.
 AVI: Video files in AVI format are sorted into the video/AVI folder.
 MP4: MP4 video files are sorted into the video/MP4 folder.
 MOV: MOV videos are sorted into the video/MOV folder.
 MKV: MKV videos are sorted into the video/MKV folder.

Documents
 DOC: Documents in DOC format are sorted into the documents/DOC folder.
 DOCX: DOCX documents are sorted into the documents/DOCX folder.
 TXT: Text documents are sorted into the documents/TXT folder.
 PDF: PDF files are sorted into the documents/PDF folder.
 XLSX: Spreadsheets in XLSX format are sorted into the documents/XLSX folder.
 PPTX: PPTX presentations are sorted into the documents/PPTX folder.

Audio.
 MP3: MP3 audio files are sorted into the audio/MP3 folder.
 OGG: OGG audio files are sorted into the audio/OGG folder.
 WAV: WAV files are sorted into the audio/WAV folder.
 AMR: AMR audio files are sorted into the audio/AMR folder.
​
Other.
 Files that don't match any of the specified formats are sorted into the OTHER folder.

Archives
 Archive files are sorted into the archives/ARCHIVES folder.

After sorting, empty folders are deleted to keep the directory clean and organized. If there are problems with deleting folders, an error message is displayed.

Зазначте шлях до каталогу, щоб використовувати цю функцію та організувати ваші файли за зазначеними критеріями.

Для використання цієї функції переконайтеся, що у вас встановлено необхідні бібліотеки та виконали встановлення за допомогою:
pip install rich


## Our team:
* Developer: [chAek](https://github.com/aektann89)
* Developer: [Andrew](https://github.com/Andrewchv)
* Developer: [Aryna Reutska](https://github.com/xrendezvous)
* Scrum Master + Developer: [Olha](https://github.com/HelgaTsar)
* Team Lead + Repository Owner + Developer: [Serg](https://github.com/CodeCraftSerg) (ex [Obi-Wan-Serg](https://github.com/Obi-Wan-Serg))
