# khizarkhizar.github.io/home

It is a personal static website/portfolio hosted with GitHub Pages, build to showcase my recent projects. Site URL / Demo: [khizarkhizar.github.io/home](https://khizarkhizar.github.io/home).

## Dependencies

Dependencies defined in package.json

- [Reactjs](https://reactjs.org/)
- [Bootstrap](https://getbootstrap.com/)
- [Typist](https://github.com/jstejada/react-typist)
- [GitHub Api](https://developer.github.com/v3/repos/)
- [Instagram Api](https://www.instagram.com/developer/embedding/)

## Structure

- Body
  - Name| Profession
  - Contact / Follow / Find me / Facebook / Linkedin / GitHub / Instagram / Email / codepen
  - Resume
- About Me
  - Display picture (using instagram api)
  - Interests, Goals and Hobbies
- Projects (using gitHub api)
  - Things I'm good at (Skills)
- Footer
  - Acknowledgements (contributors)
  - Copyrights - open source
  - (qoute: Dream big, Think big)

## Sharing

Project is open source. Feel free to make your own version. All you need to do is to fork the project and edit the [src/configurations.json](./src/configurations.json) file. Mark star if you like the project.

## Instructions

1. To Get Started, Fork the repository to your github account:
2. Clone the forked repo from your account using :

   ```bash
     git clone https://github.com/<your-username>/home.git
   ```

3. Open in editor and edit [src/configurations.json](./src/configurations.json) file.

4. Change URL in [package.json](./package.json) file

   ```json
   "homepage": "https://<your-username>.github.io/home"
   ```

5. Edit title and meta description in [public/index.html](./public/index.html).

6. After editing run the following bash commands

   ```bash
   npm install
   npm start
   ```

7. To deploy website run:

   ```bash
    npm run deploy
   ```

8. Congrats your site is up and running. To see it live , visit :

   ```https
     https://<your-username>.github.io/home
   ```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Issues

If anyone is looking to make some contribution, then following are the issues that you can solve.

- UI improvments
- Grammar check | Spelling mistakes
- Code optimization
- Hover property on social icons
- Routing

## License

[LGPL-3.0](https://www.gnu.org/licenses/lgpl-3.0.en.html)
