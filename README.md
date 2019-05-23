## Joi.js Validation ##
Whenever a user sends data in a request, it is important to validate the input. Why? Because you should never trust the user input. Validating input can stop incorrect formats, too much unnecessary data, and security breaches such as SQL injections. Validation with Vanilla Javascript can be time consuming. This is where the Joi package becomes very useful. Joi is used for validation of body, query, and URL parameters. How? Let’s take a look.

Joi Tutorial

* https://github.com/SecuringTheStack/tutorials/tree/master/ep18-input-validation-with-joi-part1
* https://www.youtube.com/watch?v=HkNdG7d_LAI&t=2s

Joi Documentation

* https://github.com/hapijs/joi/blob/v15.0.3/API.md#stringalphanum

## @Hapi/Joi ##
Joi was originally built by Hapi.js team as a plugin to support object schema validation within the Hapi framework.
It provides body, query and URL params validation in Hapi.js. Adding validation is as simple as calling the right method. It also supports validation on deeply nested objects which most of the other validation modules out there don’t.

Hapi Vs Express

* https://raygun.com/blog/hapi-vs-express/
* https://www.youtube.com/watch?v=2lprC0yYeFw

Celebrate for Joi + Express
* https://medium.com/@adambretz/time-to-celebrate-27ccfc656d7f
* https://github.com/arb/celebrate
