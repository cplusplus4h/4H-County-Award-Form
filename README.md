# 4H-County-Award-Form

[Contribution Guidelines](CONTRIBUTING.md)

## Running
After completing [Developer Setup](#DeveloperSetup):
- Open the terminal in VSC (View > Integrated Terminal)
- `meteor`
- Open your browser and go to `http://localhost:3000`

To stop the server, enter `Ctrl+C` in the terminal.

## Learn
- Khan Academy:
  - [Intro to HTML / CSS](https://www.khanacademy.org/computing/computer-programming/html-css)
  - [HTML/JS: Making webpages interactive](https://www.khanacademy.org/computing/computer-programming/html-css-js)
  - [HTML/JS: Making webpages interactive with jQuery](https://www.khanacademy.org/computing/computer-programming/html-js-jquery)
- codecademy
  - [Learn HTML](https://www.codecademy.com/learn/learn-html)
  - [Learn CSS](https://www.codecademy.com/learn/learn-css)
  - [Learn Sass](https://www.codecademy.com/learn/learn-sass)
  - [Introduction to Javascript](https://www.codecademy.com/learn/introduction-to-javascript)
  - [Learn ReactJS: Part I](https://www.codecademy.com/learn/react-101)
  - [Learn ReactJS: Part II](https://www.codecademy.com/learn/react-102)
  - [Introduction to jQuery](https://www.codecademy.com/learn/learn-jquery)
- Meteor
  - [Tutorial](https://www.meteor.com/tutorials/react/creating-an-app)
  - [Intermediate Video Tutorials](https://www.youtube.com/watch?v=BI8IslJHSag&list=PLLnpHn493BHFYZUSK62aVycgcAouqBt7V)
  - [Guide](http://guide.meteor.com/)


## <a name="DeveloperSetup"></a>Developer Setup
1. [Install Meteor](https://www.meteor.com/install)
1. Windows only: [Install git](https://git-scm.com/)
1. Configure git.  From the command prompt or terminal run:
    - `git config --global user.name "Your GitHub Username"`
    - `git config --global user.email you@youremail.com`
    - Windows
      - `git config --global credential.helper wincred`
    - Mac
      - `git config --global credential.helper osxkeychain`
1. [Install Visual Studio Code (VSC)](https://code.visualstudio.com/)
1. Configure VSC:
    - Windows
      - File > Preferences > Settings.  Set the `git.path` setting to the location of git.exe.
1. Install the following VSC Extensions:
    - Beautify
    - markdownlint
    - Debugger for Chrome
    - Meteor
    - IntelliSense for CSS class names
    - (Something for React, but not sure which ones yet)
