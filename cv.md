<h1 align="center">Hi there, I'm Timur Smagulov
<img src="https://github.com/blackcater/blackcater/raw/main/images/Hi.gif" height="32"/></h1>


## Contacts:
1. email: deikku@mail.ru
2. telegram: @dttuwu
3. discord: _deikku
4. linkedin: https://www.linkedin.com/in/timursmagulov/


## About me:
Hello, my name is Timur, I am 20 years old. I'm studying to be a front-end web developer. I started studying for a frontend developer in September 2022. Six months later, I received my first offer to the web studio. I worked there for 8 months and at the moment I am looking for a new challenge. I want to become not just a frontend developer, but an engineer. I currently live in Astana and am a student of the L.N. Gumilev Eurasian National University. However, I am persistent, fast learner and hardworking. I like frontend and I hope this school will help me achieve my goals.


## Skills:
- Programming languages: JavaScript, TypeScript
- Libraries: React JS, JQuery
- Technologies: HTML, CSS, SASS/SCSS, BEM, Redux
- Assembling: Gulp, Webpack, Vite
- CMS: October CMS
- Tools: Git, GitHub
- Frameworks: Bootstrap, Tailwind CSS
- IDE: Visual Studio Code


## Code example:
```js
const __hasProp = Object.prototype.hasOwnProperty;

function groupBy(array, prop, result = {}) {
  array.forEach((el) => {
    if (__hasProp.call(el, prop)) {
      result[el[prop]] ? result[el[prop]].push(el) : (result[el[prop]] = [el]);
    }
  });

  return result;
}
