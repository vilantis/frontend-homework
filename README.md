# Vilantis frontend homework task

Implement a small website using any front-end technology you like (preferably React.js or Vue.js) in compliance with the requirements below. Feel free to use any other additional software (e.g. libraries) as necessary. Format your code according to the style guidelines of your chosen technology. Upload your solution to a repo on GitHub. Finally, send us a link to the GitHub repository, and (if the repository is private) don't forget to add [antanas](https://github.com/antanas) as a repository member.

Implementation of all the [required] tasks is necessary for passing the test. Completing the non-required tasks gives bonus points. We also encourage you to come up with and implement your own ideas in addition to, or instead of, the optional requirements.

While working on this assignment, you are welcome to have fun, overengineer and show off your strengths.

## Additional info

#### Input .csv file example:
```
User name,Age
Elvis Presley,42
Jimmy Hendrix,27
David Bowie,69
```

#### API call example:
```
curl -X POST https://vilantis-frontend-homework.free.beeceptor.com/users \
-H 'Content-Type: application/json' \
-d '{"users":["David Bowie","Jimmy Hendrix","Elvis Presley"]}'
```

**Note: This endpoint will always return statusCode 200. During the interview we'll also simulate different responses.**

## Requirements
### Required 
- [ ] Allow the user to select and upload multiple `.csv` files (the file example is shown above).
- [ ] List all the uploaded files along with their filenames and the count of users stored in the file.
- [ ] Add an option to remove any file from the list.
- [ ] Show the average age of all the users.
- [ ] Add a "Submit" button that collects users from the uploaded files and sends them to the API endpoint.
- [ ] Show a loading state while the API request is in progress.
- [ ] If the API call succeeds - show a success message and clear all uploaded files.
- [ ] If the API call fails - show an error message and let the user retry manually.
- [ ] Add a Readme file with the instructions on how to set up and start your website.

### Optional
- [ ] If the API call fails - retry 3 times automatically. If all the retries fail - show an error message and let the user retry manually.
- [ ] Add a separate tab that shows API calls logs - failed/succeeded, user count, timestamp
- [ ] Use any component UI library that you like
