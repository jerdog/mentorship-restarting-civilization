# Mentorship, or How to rebuild civilisation from scratch
***How really important are mentorship and documentation to the survival of civilization? What would happen if we lost everything and had to start over, say, due to a global pandemic? In this talk, we’ll explore my fascination with dystopian TV shows and seek to answer these questions, and come to some action steps to do our part through mentorship, documentation, and more.***

*Presented at Connect.Tech 2022, 9 Sep 2022*   
<img src="https://github.com/jerdog/mentorship-restarting-civilization/blob/connecttech22/connectTech2022_transparent.png" width="25%" height="25" alt="Connect.Tech 2022 logo" />

### Viewing slide deck
To view the slide deck as presented, visit: https://slides.com/jerdog/connecttech22-mentorship-restarting-civilization

### Running locally
_Instructions taken from [MDN](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/set_up_a_local_testing_server)_

1. Identify which version of Python is installed
```bash
python -V
# If the above fails, try:
python3 -V
# Or, if the "py" command is available, try:
py -V
```

2. Enter directory for this repo and type one of the following:
```bash
# If Python version returned above is 3.X
# On Windows, try "python -m http.server" or "py -3 -m http.server"
python3 -m http.server
# If Python version returned above is 2.X
python -m SimpleHTTPServer
```

3. This will set the contents of the folder as a local web server on port `8000`. You can visit that via http://localhost:8000, where it will even auto load the `index.html` file or show you the contents to choose what to display.