Blackjack Makerthon!
===

Construction of an MVP Blackjack App made by Ronin July 2015 cohort in two days. 


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
- JQuery
- HTML
- CSS
- Rspec
- Shoulda
- Capybara


Screenshot
---

![alt text](https://github.com/winnieau/blackjack/blob/master/app/assets/images/blackjack_screenshot.png)


Find a link to our deployed Blackjack app [here](https://pure-refuge-7844.herokuapp.com/)
