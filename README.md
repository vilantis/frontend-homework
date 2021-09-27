# Vilantis frontend homework task

Implement a small web site using any frontend technology you like (preferably React.js or Vue.js) in compliance with the requirements below. Use any additional software necessary. Format your code according to the recommendations of your chosen technology. Add a Readme file with the instructions how to set up and start your website. Upload your solution to a repo on GitHub. If it's a public repo - just send us the link. If it's a private on - invite user [antanas](https://github.com/antanas).

Implementation of all the [required] lines is necessary for passing the test. Implementation of the non-required lines gives bonus points. Feel free to come up with and implement your own ideas in addition to, or instead of, the optional requirements.

While working on this assignment, your are welcome to have fun and show off your strengths.

## Additional info
`.csv` file example:
```
User name, Age
Elvis Presley,42
Jimmy Hendrix,27
David Bowie,69
```

api call example:
```
curl -X POST https://frontend-homework.getsandbox.com/users
   -H 'Content-Type: application/json'
   -d '{"users":["David Bowie","Jimmy Hendrix","Elvis Presley"]}'
```
Note: api randomly fails (on purpose) with 500

## Requirements
### Required 
- [ ] Allow the user to select multiple `.csv` files (file example is shown above)
- [ ] List all selected files together with their filenames and line counts
- [ ] Add an option to remove any file from the list
- [ ] Show the average of age of all the users
- [ ] Add a "Submit" button that collects users from files and sends them to api (more info above)
- [ ] Show a loading state while api request is in progress
- [ ] If the api call succeeds - show success message and clear all uploaded files
- [ ] If the api call fails - show an error message and let the user retry manually.

### Optional
- [ ] If the api call fails - retry 3 times. If all retries failed - show an error message and let the user retry manually.
- [ ] Add a separate tab that shows api calls logs - failed/succeeded, user count, timestamp
- [ ] Use any component UI library that you like
