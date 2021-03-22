# Denali Themes

Contains custom themes created by contributors and the Denali Team.

---

## Add your theme

Add a custom Denali theme and have it showcased on our website. All themes must be fully customized to be accepted.

> If you want to read a step by step guide on how to create a theme using Denali be sure to read our [Theming Guide](https://denali-design.github.io/denali-css/?path=/story/get-started-theming--page).

### Install Prerequisites 

1. [Nodejs](https://nodejs.org/)
2. [NPM](https://www.npmjs.com/)
3. [Sass](https://sass-lang.com/)

### Create your theme

1. Navigate to the themes folder

2. Duplicate the `_THEME-TEMPLATE` folder and rename it to your theme name.

3. Rename the THEME.scss file in the `css` folder.

4. Install Node Modules.

```
npm install
```

5. Compile the `SCSS` using the command below. 

> Be sure to update the path to the `SCSS` and `CSS`.

```
sass --watch --no-source-map PATH-TO-THEME-FILE/THEME.scss:PATH-TO-OUTPUT-FILE/THEME.css
```

6. In the index.html file update the link your compiled `css` file.

7. If you changed the name of your body class in the Sass mixin, make sure to update that as well.

---

## Contributing

See the [Contributing](CONTRIBUTING.md) guide for details.

---

## License

This project is licensed under the [MIT License](LICENSE.md).
