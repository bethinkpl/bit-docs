# Cookie

**Prerequisite knowledge:** http, 

## Intro
An HTTP cookie is a piece of text that is transferred (both ways) between browser and server on every request. They were designed to handle the state of the application. Most common use-cases for cookies are Session handling and 3rd user party tracking.

## Classification / acceptance questions

### Apprentice aka _I can CRUD cookies_
* I can create, read, update and delete cookies on server and browser side
* I can set expire time on a cookie
* I can use Path attribute to restrict where cookie can be used

### Intermediate aka _I can use cookies in real app_
**Prerequisite knowledge:** session
* I can set up a web session using cookies
* I can share session between subdomains using cookies Domain attribute
* I understand how 3rd party tracking pixels benefit from using cookies   

### Wizard aka _I can hack cookies_
**Prerequisite knowledge:** web security
* I can perform and protect from CSRF attack using SameSite flag, CSRF token or by validating Origin header
* I can protect a cookie from XSS attack using HttpOnly flag
* I understand differences between cookies, SessionStorage and LocalStorage

## Sources

### Read online
- [HTTP cookie on Wikipedia](https://en.wikipedia.org/wiki/HTTP_cookie)
