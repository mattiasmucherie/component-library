These first three steps has already been done for you but if you wanna create a new project, you know how to do it.

1. Create a new Vite project.
1. Install the dependencies needed for MUI (Material UI). We will install the icons and the font as well.

   ```bash
     npm install @mui/material @emotion/react @emotion/styled @fontsource/roboto @mui/icons-material
   ```

1. You need to import the font in `main.jsx`

   ```js
   import "@fontsource/roboto/300.css";
   import "@fontsource/roboto/400.css";
   import "@fontsource/roboto/500.css";
   import "@fontsource/roboto/700.css";
   ```

1. I've created a component called MediaCard that shows how we can use MUI to create components.

   Explore and take a look at it. It comes straight from their [docs](https://mui.com/material-ui/react-card/#media)

## TASK

In smaller groups, create a website that uses MUI. The website can be whatever you want, maybe fetch something from an API, do a TODO app or show some cooking recipes using Material UI.

> Have a look at the [documentation](https://mui.com/material-ui/react-button/) to see what components there are available.
