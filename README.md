# BermudaBox
Exploring the idea of using [Time-based One-time Passwords (TOTP)](https://en.wikipedia.org/wiki/Time-based_One-time_Password_Algorithm), typically used in [2FA (Two-Factor Authentication)](https://en.wikipedia.org/wiki/Two-factor_authentication) via [Google Authenticator](https://support.google.com/accounts/answer/1066447?hl=en), as an alternative protection against [Cross-Site Request Forgery (CSRF)](https://www.owasp.org/index.php/Cross-Site_Request_Forgery_%28CSRF%29) and automated attacks (usually protected by [CAPTCHA](https://en.wikipedia.org/wiki/CAPTCHA)). This project also explores the idea of using TOTP as an alternative [Stateless](http://stackoverflow.com/questions/844536/advantages-of-stateless-programming) authentication method.