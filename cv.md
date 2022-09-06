# rsschool-cv

# Artem Mironchik

### Contact Info:
  * **Phone**: +375447528453
  * **Email**: tawerka.power@gmail.com
  * **Discord name**: @artemmironchik
  * **Telegram**: @kichnorim   

***

### About me:
I'm currently a student of BSU and my passion for knowledge and new challenges might be the reasons why I decided to start this course. I don't have any working experience yet but I think that my communication skills, dedication to work, ability to work in team and the knowledge that I will get from this course will be a good addition to any company.      

***

### Skills:
  * HTML5, CSS3
  * Basic knowledge of JavaScript and C++
  * Figma, Adobe Illustrator (basics)
  * Git   

***

### Code example:
**Where my anagrams at ? (Codewars, 5kyu)**: What is an anagram? Well, two words are anagrams of each other if they both contain the same letters. For example: `'abba' & 'baab' == true`. Write a function that will find all the anagrams of a word from a list. You will be given two inputs a word and an array with words. You should return an array of all the anagrams or an empty array if there are none. For example: `anagrams('abba', ['aabb', 'abcd', 'bbaa', 'dada']) => ['aabb', 'bbaa']`.
```
function anagrams(word, words) {
  let newWord = word.split('').sort().join('')
  console.log(newWord)
  return words.filter(wordInArr => {
    let sortedWord = wordInArr.split('').sort().join('')
    if (sortedWord === newWord) {
      return wordInArr
    }
  })
}
```
***
### Courses:
  * 1 year of learning basics of HTML, CSS and JS in the university
  * Currently learning JS on [learn.javascript.ru](learn.javascript.ru)
  * 2 years of learning English with tutor   

***

### Languages:
  * English - C2 according to the [EFSET Certificate](https://www.efset.org/cert/X3WbJc), had some practice with native speakers
  * Russian - Native
  * Belarussian - can understand it, but don't know it to the level where I can speak on it
