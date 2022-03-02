## Olga Alexandrova

### Contacts

- **Location:** Moscow
- **Telegram:** Alex_jkz
- **Discord:** jkz(@AlexOlga)
- **GitHub:** [AlexOlga](https://github.com/AlexOlga)

### About me

I want to learn Front-End Development. My goal is to gain knowledge in the field of front-end development.

### Skills

- HTML, CSS;
- JavaScript Basics;
- Redmine
- Adobe Photoshop, Figma (for web development);

### Code Examples

**Task:** Your task is to implement the so-called 'towel sort' algorithm. TtowelSort function should expect matrix of any shape for example:

```
[
 [ 1, 2, 3 ],
 [ 4, 5, 6 ],
 [ 7, 8, 9 ],
]
```

Following matrix should be 'sorted' to:
[1, 2, 3, 6, 5, 4, 7, 8, 9 ]

```
function towelSort (matrix) {
  if ( arguments.length==0){return []}
  else{
  let newArr=[];
 if ( matrix==[]) {return []}
 else{
  for (let i=0; i<matrix.length; i++){
      matrix[i].sort((a, b) => a - b );
        if (i%2 != 0){
      matrix[i].reverse();
      }
  }
  matrix.forEach(item => { newArr=newArr.concat(item);});
  return newArr;}
}
}
```

### Educational projects

- [Eco-sounds](https://rolling-scopes-school.github.io/alexolga-JSFEPRESCHOOL/js30-eco-sounds/)
- [Image-galery](https://rolling-scopes-school.github.io/alexolga-JSFEPRESCHOOL/image-galery/)
- [Memory-game](https://rolling-scopes-school.github.io/alexolga-JSFEPRESCHOOL/memory-game/)

### Education

- Saratov State University
  - Faculty of Mathematics and Mechanics
- RS SCHOOL JS/FE Pre-Shool 2022
- RS SCHOOL JS/FE 2022Q1 (training ongoing)

### Languages

- Russian - Native
- English (A0)
