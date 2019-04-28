# Goldfish

In this repository is the Volter (Goldfish) font and its bold variation, Volter-Bold, which are both pixel-style sans-serif fonts created by [Sulake](http://www.sulake.com/).

---

<img src="./demo.png">

## Setup

To set up the font faces:

- Make sure the font files are in the correct directory
- Copy the `volter` and `volter-bold` directories, along with `goldfish.css`, to your application
- Import the `goldfish.css` file in any CSS file you wish to use it in

  ```scss
  @import url("path/to/goldfish.css");
  ```

Then you can start using the font faces:

```scss
@import url("goldfish.css");

// Volter (Goldfish)
h1 {
  font-family: 'Volter';
}

// Volter-Bold (Goldfish)
h1 {
  font-family: 'Volter';
  font-weight: bold;
}
```

**Demo webpages for the fonts can be found in each of their respective directories**

## License

Licensed under the **Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)** license.

<p align="center"><a href="https://creativecommons.org/licenses/by-sa/4.0/legalcode"><img src="https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg" width="100px"></a></p>