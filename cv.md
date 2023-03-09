# Artyom Pizin

======================================

## Contacts

- **Location:** Petrovskoye, Luhansk region, Ukraine
- **Email:** artempetr2016@gmail.com
- **Discord:** Motopes (@SEPOTOM)
- **VKontakte:** [Pizin Artyom](https://vk.com/vselenskii.motopes)
- **Telegram:** [Pizin Artyom](https://t.me/M0T0PES)
- **GitHub:** [SEPOTOM](https://github.com/SEPOTOM)

## About Me

In high school, I started to get interested in website development and realized that this is what I want to do. I am calm, patient, diligent, have no problems in communication. I am constantly studying new technologies, I have good learning ability. I am striving to become a Frontend developer!

======================================

## Skills

- HTML
- CSS
- SCSS
- BEM
- Basic JS
- Git
- GitHub
- Chrome DevTools
- Figma for developer

## Code examples

My solution for the 6 kyu kata [Base Conversion](https://www.codewars.com/kata/526a569ca578d7e6e300034e/solutions/javascript) from Codewars:

```
function convert(input, source, target) {
  const sourceArr = source.split('');
  const inputArr = input.split('').map((num) => {
    return sourceArr.indexOf(num);
  });
  const targetArr = target.split('');

  let decemalVal = inputArr.shift();

  while(inputArr.length) {
    decemalVal = decemalVal * sourceArr.length;

    if(inputArr[0]) {
      decemalVal += inputArr[0];
    }

    inputArr.shift();
  }

  while(true) {
    inputArr.unshift(decemalVal % targetArr.length);
    decemalVal = Math.floor(decemalVal / targetArr.length);

    if(decemalVal <= (targetArr.length - 1)) {
      inputArr.unshift(decemalVal);
      break;
    }
  }

  while(targetArr[inputArr[0]] === targetArr[0] && inputArr.length > 1) {
    inputArr.shift();
  }



  return inputArr.map((idx) => {
    return targetArr[idx];
  }).join('');
}
```

## Projects

- ***CV:*** [https://SEPOTOM.github.io/rsschool-cv/cv](https://SEPOTOM.github.io/rsschool-cv/cv)
- ***GERÍCHT:*** [https://sepotom.github.io/gericht/](https://sepotom.github.io/gericht/)

## Education

- Secondary education
- A [course](https://edu.fls.guru/) on layout from a Freelancer for life
- RS Schools [course](https://rs.school/js-stage0/) «JavaScript/Front-end. Stage 0»

## Languages

- **Russian:** Native
- **Ukrainian:** Native
- **English:** Pre Intermediate (A2)
