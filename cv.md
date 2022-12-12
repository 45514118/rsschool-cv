![GitHub avatar](https://avatars.githubusercontent.com/u/19572532?s=120&v=4)

# Dinar Agzyamov

#### Front-end developer

### Contacts

- tel: +7 927* 42* 95\*
- email: mail@deenar.ru
- github: @45514118

### Goal

I'm intested in web development & want to become front-end developer.

### Skills

- HTML5, CSS3
- JavaScript
- Git

### Code example

##### Task:

Write a function that takes in an array containing a gym member´s personal details.

##### Solution:

```
    function calorie (member){
      let RMR
      if(member[1]==="m") {
        RMR = 10 * member[4] + 6.25 * member[3] - 5 * member[2] + 5
      } else {
        RMR = 10 * member[4] + 6.25 * member[3] - 5 * member[2] - 161
      }
      let activityFactor
      if(member[5]==="little activity") {
        activityFactor = 1.2
      } else if(member[5]==="moderately active") {
        activityFactor = 1.55
      } else if(member[5]==="very active") {
        activityFactor = 1.7
      } else if(member[5]==="extremely active"){
        activityFactor = 1.9
      }
      const calorieRequirement = RMR * activityFactor
      return `${member[0]}´s daily calorie requirement is ${(Math.round(calorieRequirement * 100)/100).toFixed(2)} kcal.`
    }
```

### Courses

- GoIT HTML & CSS (completed)
- Goit Javascript (completed)
- RS School JavaScript/Front-end.Stage0 (in progress)

### Projects

- [https://45514118.github.io/goit-markup-hw-08/](https://45514118.github.io/goit-markup-hw-08/) - HTML & CSS Practice (solo project)
- [https://korobass87.github.io/Weather-GOIT/](https://korobass87.github.io/Weather-GOIT/) - JavaScript Practice (team project)
