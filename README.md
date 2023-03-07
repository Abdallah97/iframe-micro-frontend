# 👋🏼 Micro Frontend with `<iframe>`!

This project demonstrates a micro frontend architecture using iframes, with an Angular application serving as the body and two React applications serving as the header and footer.

To get started, follow these simple steps:

1.  Install the necessary packages for each application:

   -   You can run `npm run install-apps` or navigate to the each directory (`angular-body`, `react-header`, `react-footer`) and run `npm install`.
2.  Start each application:

   -   Serve each one:
      -   For `angular-body`, navigate to the directory and run `npm start`. This will start the application on `localhost:3001`, which serves as the body.
      -   For `react-header`, navigate to the directory and run `npm start`. This will start the application on `localhost:3002`, which serves as the header.
      -   For `react-footer`, navigate to the directory and run `npm start`. This will start the application on `localhost:3003`, which serves as the footer.
   -   Or you can server each application with these commands: `serve-angular-body`, `serve-react-header`, `serve-react-footer`.
3.  Once all three applications are running, you can open the `app-container.html` file in your browser to see the micro frontends in action.

   -   You can do this by running the following command from the project's root directory `npm run open`.

🌳 Here's the directory tree showing only the main directories for each application:

cssCopy code

`├── angular-body
│   ├── src
│   └── package.json
├── react-header
│   ├── src
│   └── package.json
├── react-footer
│   ├── src
│   └── package.json
├── app-container.html
└── style.css`

Note that each application has its own `src` directory.

🚀 Enjoy your micro frontends!

Final Result
------------

![alt text](https://chat.openai.com/docs/iframe-mfe.png "Micro Frontend - iframe")

License
-------

This project is licensed under the MIT License. See the `LICENSE` file for details.
