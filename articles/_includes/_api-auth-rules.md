- Redirect rules won't work. If you try to do a [redirect](/rules/redirect) by specifying `context.redirect` in your rule, the authentication flow will return an error.
- If you try to do MFA by specifying `context.multifactor` in your rule, the authentication flow will return an error.