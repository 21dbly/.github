# Start up deliverable - JavaScript

Now that you have learned how to make an application interactive, it is time to add some JavaScript to your start up application. The main thing you should focus on in this deliverable is making your application minimally viable. The application doesn't have to do everything it will do once you are done, but it should be completely usable to some extent at this point.

You must use the same start up GitHub repository that you created with your earlier start up deliverables. Update the README.md file with things that you learn as you work on your start up. As you make changes to your HTML, CSS, and JavaScript commit those changes and push them to GitHub. You will need at least four commits to get full credit, but in reality you should have many more than that. If you are using pair programming then your commit history should reflect contributions from all contributing peers.

Leverage what Simon teaches in order to learn how to read login information, represent database data, and save and display data in `localstorage` between pages and browser sessions.

Remember to use the `VS Code Live Server` extension to see what your code looks like in the browser. Also use the browser's debugger window to debug your CSS and JavaScript. This will save you a lot of time if you learn how to leverage these tools.

Once you have developed your application to where you want it, you need to release it to your production environment. **Replace** your previous start up deployment script with a copy of the `deployFiles.sh` script from the [Simon JavaScript repository](https://github.com/webprogramming260/simon-javascript/blob/main/deployFiles.sh) and use `startup` for the service parameter (`-s`)

```sh
./deployService.sh -k <yourpemkey> -h <yourdomain> -s startup
```

For example,

```sh
./deployService.sh -k ~/keys/production.pem -h yourdomain.click -s startup
```

Doing this will make this deliverable of your start up available from `https://startup.yourdomainname`.

## ☑ Assignment

1. Add significant use of JavaScript to your start up application.
1. Represent each of the required technologies with JavaScript placeholders.
   1. Have JavaScript that takes user input and adds it to the mocked database data. This should be something simple like an array or object in your JavaScript that will eventually be replaced by service endpoint database calls.
   1. Have JavaScript that reads the login input and displays the user name.
   1. Have JavaScript that mocks your database data and injects it into the DOM.
   1. Use the `localstorage` API to keep data between pages and browser sessions.
   1. Have JavaScript that mocks out the realtime data you expect to get from the server using WebSocket and inject it into the DOM.
1. Make sure all authors of the code are attributed in the application and that there is a link to your GitHub repository.
1. Periodically commit and push your code to GitHub.
1. Periodically update your start up repository's README.md file to reflect what you have learned and want to remember.
1. Push your final version of your project to GitHub.
1. Deploy your start up application to your production environment (your server).
1. Make sure your application is available from your production environment.
1. Upload the URL to your start up application to the Canvas assignment.

## Grading Rubric

- Significant use of JavaScript to create a minimally viable working application.
  - 20% JavaScript support for future login.
  - 20% JavaScript support for future database data.
  - 10% JavaScript support for future WebSocket.
  - 30% JavaScript support for your application's interaction logic.
- 10% - Multiple Git commits with meaningful comments.
- 10% - Notes in your start up Git repository README.md file documenting what you have learned using JavaScript.

## Go celebrate

You did it! This is a significant milestone. Time to grab some friends, show them what you did, and celebrate with ice cream 🍦.
