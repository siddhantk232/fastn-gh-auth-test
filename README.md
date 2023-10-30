# Fastn GH Auth Test

### Requires:

- FASTN_GITHUB_CLIENT_SECRET
- FASTN_GITHUB_CLIENT_ID

The `fastn` doesn't recognise these tho?

## Bug

- ftd.navigate("http://localhost:8000/-/auth/login/" + "?next=http://localhost:8000/check")
   `ftd.navigate()` works differently in brave and firefox
    Works as expected in firefox. Redirects to url with correct query params.
    In brave, redirects to `localhost/check`. Needs investigation

