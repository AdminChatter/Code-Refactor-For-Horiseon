# <Accessibility refactor for Horiseon website>

## Description

- The code for website is too hard to read. There is too much <div> function used in the file, which makes it hard to read. And repeated used propreties which can be merged together. 
- I used varies semantic elements inside the html to makes the code more appealing to the user. Some of the code in css file is deleted and merge into one unique function.
- In this project, I learnt what each semantic element is and how they fit into their location. For example for indivdual image section the code and start with <figure> instead of <div>. And during research, I learnt the image link in css file can not have an ALT text. So I learnt how to add the ALT text with the add-on feature ".visually-hidden", which need to be created and defined in the css stylesheet.
    

## Installation

Simply just launch the page, and that's it.

## Usage

![Website picture.jpg](assets/Image/Website%20Page.jpeg)

## Credits

Chat-GPT

## License

Currently no idea what this is, and have no more time for research QAQ

## Badges

N/A

## Features

- .visually-hidden, it stop the conflict between css and html image url link which allowed me to add ALT text without removing the image url in css

![visually-hidden code.png](assets/Image/Visually-hidden.png)

## How to Contribute

Currently this project is open source in my github: https://github.com/AdminChatter/Code-Refactor-For-Horiseon. If you wanna help me out, please give me a heads up.

## Tests

N/A