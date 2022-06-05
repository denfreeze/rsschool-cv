# Denis Morozov

## Contacts

- Location: Saint-Petersburg, Russia
- Phone: +7(981)-146-33-03
- Email: gm.denbrown2007@gmail.com
- GitHub: denfreeze

## About me
Active, positive, purposeful. Great desire to learn new things and achieve new goals.

## Code example
```
function getRandomElement(arr) {
  let randIndex = Math.floor(Math.random() * arr.length);
  return arr[randIndex];
}

let button = document.querySelector('.button');
let phrase = document.querySelector('.phrase');
let advice = document.querySelector('.advice');
let image = document.querySelector('.image');

button.addEventListener('click', function () {
  let randomElement = getRandomElement(phrases);
  phrase.textContent = randomElement;
  if (randomElement.length > 40) {
    advice.style.fontSize = '33px'
  }
  else {
    advice.style.fontSize = '42px'
  }
});
```
## Skills
- HTML/CSS (Beginner)
- JavaScript (Beginner)

## Education
- University: Saitn-Petersburg Mining Uneversity.

## English
- A2