# CSYMApp - CSyber Systems Mother Application
A boiler plate for developing **Node.js** web applications implementing user account management and access control.

## Project Signature
Project | **Csyber Systems Mother Application**
---|----------------
Developer | Brian Onang'o
Email  | [Brian Onang'o](mailto:brian@cseco.co.ke), [Brian Onang'o](mailto:surgbc@gmail.com)
for  | CSECO - Circuits and Systems Engineering Company
Start Date  | 2017 

## Table of Contents
- [CSYMApp](#csymapp)
- [Justification](#justification)
- [Features](#features)
- [Usage](#usage)
- [Parts](#parts)
- [Parts](#references)

## CSYMApp
CSYMApp is a boiler plater for developing Node.js web applications. It's particularly useful where user account management and access control is to be implemented. We have in CSYMApp implemented our version of [Role Based Access Control (RBAC)](https://en.wikipedia.org/wiki/Role-based_access_control) which we call [Familyfe Role Based Access Control](https://github.com/csymapp/Familyfe_RBAC/). CSYMApp also implements a hierarchical relationship between groups of users (which we call families) as would exist in natural families or in an organization, making it easy to implement access control in applications which are to be used in one organization or across multiple organizations. For more information, please refer to the docu
mention given for the [individual components](#parts) that together make up CSYMApp.

## Justification
*"...how often would I have gathered thy children together, even as a hen gathereth her chickens under her wings" Matthew 23:37*. When we take care of the mother (application), the child applications will be easier to take care of, for the mother will take care of them.

## Features
- Local Authentication using Email and Password
- OAuth 1.0a Authentication via Twitter
- OAuth 2.0 Authentication via Facebook, Google, GitHub, LinkedIn, Instagram
- Account Management
- Profile Details
- Change Password
- Forgot Password
- Reset Password
- Link multiple OAuth strategies to one account
- Delete Account
- CSRF protection
- API Examples: Facebook, Foursquare, Last.fm, Tumblr, Twitter, Stripe, LinkedIn and more.
- Group hierarchy

## Usage
You will require to put together the different [parts](#parts) to get the csystem up and running.

## Parts
CSYMApp provides an api and a separate front-end for both web and mobile applications. These should be put together to get the system up and running.
- [csymapp-api](https://github.com/csymapp/csymapp-api)
- [csymapp-web](https://github.com/csymapp/csymapp-web)
- [csymapp-mobile](https://github.com/csymapp/csymapp-mobile)

## References
- [hackathon-starter](https://github.com/sahat/hackathon-starter)

## Applications
We will populate this list with applications which have been built using CSYMApp