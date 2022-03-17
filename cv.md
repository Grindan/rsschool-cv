# Polina Korolyeva

## Contacts:

-   **Phone**: [+375 29 3680745 ](tel:80293680745)
-   **Email**: [polina.koroleva@gmail.com](mailto:polina.koroleva@gmail.com)
-   **Discord**: Grindy#7131

## About myself

I've graduated BSUIR and have already been working as software engineer for ~4 years. Assigned for the course with my friend for the ride. So my main goal is to revise basic FE topics :)

## Skills

-   Git - 19
-   CSS - 19
-   HTML - 17
-   JavaScript - 16
-   React - 13
-   Redux - 12

## Code example

_Decided to attach the solution for one of codewars katas: [**Let's Recycle!**](https://www.codewars.com/kata/5b6db1acb118141f6b000060)
The list of objects with `type`, `material` and `?secondMaterial` properties was given. The task was to sort objects across the 4 recycling bins._

```js
function recycle(array) {
    const materials = ['paper', 'glass', 'organic', 'plastic'];
    const obj = array.reduce((acc, el) => {
        acc[el.material] = acc[el.material] || [];
        acc[el.material].push(el.type);

        if (el.secondMaterial) {
            acc[el.secondMaterial] = acc[el.secondMaterial] || [];
            acc[el.secondMaterial].push(el.type);
        }

        return acc;
    }, {});

    return materials.map((el) => obj[el] || []);
}
```

## Education

-   BSUIR, FCSN, 2014-2018, Bachelor degree

## Work experience

It's my first cv that will be deployed so I have nothing to share with you. _(Commercial projects are the secret)_

## Languages

-   Russian: Native
-   English: Intermediate
-   Polish: Basic
