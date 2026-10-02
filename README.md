# JS Endpoint Finder 🔎

A lightweight JavaScript bookmarklet for quickly finding potential endpoints referenced in a web application.

Built for **bug bounty hunting and authorized security testing**.


## Demo

![JS Endpoint Finder Demo](demo.png)

## Features

* Extracts potential endpoints from HTML
* Searches inline JavaScript
* Fetches and searches external JavaScript files
* Filter discovered endpoints
* Copy individual endpoints
* Copy all endpoints
* Highlights interesting paths such as:

  * `/api`
  * `/auth`
  * `/login`
  * `/admin`
  * `/graphql`
  * `/internal`
  * `/health`

## Installation

1. Download or copy [`bookmarklet.js`](bookmarklet.js).
2. Create a new browser bookmark.
3. Paste the JavaScript from `bookmarklet.js` into the bookmark URL field.
4. Open a target that you are authorized to test.
5. Click the bookmarklet.

## Usage

Run the bookmarklet on a web application.

It will scan:

```text
HTML
Inline JavaScript
External JavaScript files
```

Potential paths will then appear in a panel on the right side of the page.

Use the **Filter** box to search for specific endpoints and **Copy All** to copy the results.

## Example Output

```text
/api/v1/users
/api/v1/account
/auth/login
/graphql
/admin/users
/internal/status
/api/config
```



**Maniesh-Neupane**

`pwn4arn`

Bug Bounty Hunter | Security Researcher
