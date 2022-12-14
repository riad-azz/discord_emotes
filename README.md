# Discord Emotes

Send discord emotes without nitro

## Description

Simple GUI app to send emotes from all joined servers without nitro

## Getting Started

### Dependencies

* Tkinter ([CustomTkinter-UI](https://github.com/TomSchimansky/CustomTkinter) that was made by [Tom Schimansky](https://github.com/TomSchimansky) to improve the tkinter look)
* multiprocessing
* requests library

### Installing the program

* Downloading the repo
```
git clone https://github.com/riad-azz/discord_emotes.git
```

_Make sure you are in the discord_emotes folder before running the upcoming commands_
```
cd discord_emotes
```

* Install the requird libraries
```
pip install -r requirements.txt
```

* Running the program as a script
```
python main.py
```

* Running the program as exe
```
pyinstaller --onefile --noconsole --windowed --add-data "C:/Users/<user_name>/AppData/Local/Programs/Python/Python310/Lib/site-packages/customtkinter;customtkinter/" main.py
```

_You can now head to discord_emotes/dist and run the main.exe file_

### Using the program

The application consist of 2 parts :

* First part will download all the info needed and emotes from all servers by using your auth token( this is a one time thing).

![Auth Token screen](readme/auth_screen.png)

* Second part will be the interface used to select servers and send emotes.

![Emotes screen](readme/emotes_screen.png)

* On the top side you can pick what server you would like to get emotes from

* On the bottom side you pick what Text Channel you would like to send the emote to by picking the server then the channel


## Help

If you dont know how to get your discord token

you can check this video from [Online Tech Tips](https://www.youtube.com/watch?v=1dva3YqBI2E) on youtube to help you.

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/1dva3YqBI2E/0.jpg)](https://www.youtube.com/watch?v=1dva3YqBI2E)


## License

This project is licensed under the [MIT] License - see the LICENSE.md file for details
