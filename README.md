Blackjack Makerthon!
===

Construction of an MVP Blackjack App made by Ronin July 2015 cohort in two days. 

[![Blackjack Demo](https://j.gifs.com/m894NJ.gif)](https://youtu.be/76VCk903ypk)

Click on the gif for a link to the YouTube video.


Basic rules
---

- [x] Player goes bust if over 21
- [x] Picture cards are worth 10 points
- [x] Ace is worth 1 or 11
- [x] Player is dealt minimum 2 cards
- [x] Player can continue to hit until he goes bust


Initial Planning with Domain Model
---
|   Object   |                        Messages                            |
|------------|------------------------------------------------------------|
|    Game    |                      deal, winner                          |
|    Hand    |    hit, stand, total, finished?, sort, ace_count, view     |
|    Deck    |                        shuffle                             |


"Game" and "Hand" were separate classes, while "Deck" was a module included inside the Game class. Some of the methods were later tweaked. 


Technologies Used
---

- Ruby on Rails
- JavaScript
- Trello
- JQuery
- HTML
- Atom
- CSS
- Rspec
- Byebug
- Shoulda
- Capybara
- Evernote 
- Poltergeist
- Database Cleaner


Screenshot
---

![alt text](https://github.com/winnieau/blackjack/blob/master/app/assets/images/blackjack_screenshot.png)


Find a link to our deployed Blackjack app [here](https://pure-refuge-7844.herokuapp.com/)

Others who contributed to this project: 
---

* [Parminder Sanghera](https://github.com/ajitsy)
* [Josh Tatterton](https://github.com/JoshuaTatterton)
* [Richard Charman](https://github.com/RichardCharman)
* [Balint Nemes](https://github.com/squarebe)


About me 
---

I am [Winnie Au](https://github.com/winnieau), a junior full-stack developer from [Makers Academy](http://www.makersacademy.com/) Ronin cohort July 2015!
