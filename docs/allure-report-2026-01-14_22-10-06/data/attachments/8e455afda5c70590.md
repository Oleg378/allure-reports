# Page snapshot

```yaml
- navigation:
  - link "Home":
    - /url: /
  - list
- main:
  - img
  - heading "Login to Frappe" [level=4]
  - form:
    - text: Email
    - textbox "Email"
    - img
    - text: Password
    - textbox "Password"
    - img
    - text: Show
    - paragraph:
      - link "Forgot Password?":
        - /url: "#forgot"
    - button "Login"
    - paragraph: or
    - link "Login with Email Link":
      - /url: "#login-with-email-link"
```