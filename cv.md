# Hauzinski Vitali
**E-mail:** hauzinski@gmail.com

**My purpose:** getting pleasure from work, improving existing skills, developing new skills. Become a frontend developer.
**My strengths:** excellent planning, goal setting and timing, technical mindset, introvert.
**Work experience:** worked in the field of construction (more than 6 years), technical maintenance, quality control.

## Skills
**Computer languages:**
- _**Java** and **Kotlin**_ -- initial level (for familiarization);
- ***Python*** -- basics, experience in writing small scripts and applications;
- ***JavaScript*** -- basics, experience in writing small scripts and applications;
- _**HTML** and **CSS**_ -- intermediate level (layout of sites for educational purposes);
- ***SQL (MySQL)*** -- entry level (write queries for educational purposes);
- ***Markdown*** -- advanced level.

**Development environments, editors and tools:** IntelliJ IDEA, PyCharm, Sublime Text, Visual Studio Code, MySQL Workbench, GIT, Figma.

## Friday the 13ths function (JavaScript)
The function `fridayTheThirteenths` accepts a `start` year and an `end` year (inclusive), and returns all of the dates where the 13th of a month lands on a Friday in the given range of year(s).   You can see the kata [here](https://www.codewars.com/kata/540954232a3259755d000039).
```
function fridayTheThirteenths(start, end) {
  let answer = [];
  end = end || start;
  for (let year = start; year <= end; year++) {
    for (let month = 1; month <= 12; month++) {
      if (new Date(year, month - 1, 13).getDay() == 5) {
        answer.push(month + "/13/" + year);
      }
    }
  }
  return answer.join(" ");
}
```
**My CodeWars' profile:** [Hauzinski](https://www.codewars.com/users/Hauzinski)

## Education
  
**I study the following resources on my own:**
- _**HTML** and **CSS**_ -- [htmlbook.ru](http://htmlbook.ru), [code-basics.com](https://ru.code-basics.com), [webref.ru](https://webref.ru), [htmlacademy.ru](https://htmlacademy.ru), [Яндекс практикум](https://praktikum.yandex.ru);
- ***JavaScript*** -- [learn.javascript.ru](https://learn.javascript.ru);
- Started, but didn't finish the cource "JS / FRONT-END" ([RS School](https://rs.school/)) - not enough knowledge of JavaScript;
- Learned the basics of testing.

**Passed education at streamline school at level A2 (Elementary)** I study the language on my own on the site [lingualeo.com](https://lingualeo.com).