# Test Netatmo Credentials
A very simple way to test the netatmo api.
You need to have an account and app set up at netatmo (https://dev.netatmo.com).

This is simple HTML page. It consists of two forms to submit values to the netatmo API.

Form 1:
- Enter your credentials
- Hit "send"
- if all went well, you see a plain JSON output
- A token is generated. It looks like "hAdkneiansne2Gjk|hAdkneiansne2Gjk"
- Copy the whole token
- hit "back" in browser to see the forms again

Form 2:
- Enter the required details
- paste the token from previous form
- hit send
- if all went well, you see a plain JSON output

Yes. Very basic. But maybe handy for debugging the API for errors like "error: invalid_client"...
