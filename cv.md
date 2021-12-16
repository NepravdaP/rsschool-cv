# Pavel Harmaza

## Contacts

- **Location:** Minsk, Belarus
- **Phone:** +375(33)346-83-65
- **Email:** pavelharmaza@gmail.com
- **GitHub:** [NepravdaP](https://github.com/NepravdaP)

## About Me

I have a goal to start career as a Front-end developer cause i love interfaces and their features. And generally like to learn something new. I have good social skills and seek responsibility to better live in digital

## Skills

- HTML
- CSS
- JavaScript(basic)
- Adobe Photoshop(color correction and meme making)

## Code Example

```
//Function that convert color from RGB to Hex
function rgb(r, g, b) {
  let arrRgb = [r, g, b];
  let final = "";
  for (let i = 0; i < arrRgb.length; i++) {
    if (arrRgb[i] <= 0) {
      final += "00";
      // console.log(final);
    } else if (arrRgb[i] > 255) {
      final += "FF";
      // console.log(final);
    } else if (arrRgb[i] < 16) {
      final += "0" + arrRgb[i].toString(16);
    } else final += arrRgb[i].toString(16);
    // console.log(final);
  }

  return final.toUpperCase();
}
```
