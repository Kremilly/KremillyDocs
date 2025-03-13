The CVE API provides access to information about known security vulnerabilities in software, access information about known security vulnerabilities in software.

## Example of request

```shell
https://api.kremilly.com/cve?id=YOUR_CVE_ID
```

> *Replace `YOUR_CVE_ID` with the CVE id*

### A simple example of use in JavaScript

```javascript
// Replace "YOUR_CVE_ID" for your CVE
fetch('https://api.kremilly.com/cve?id=YOUR_CVE_ID').then(
   json => json.json()
).then(callback => { 
   console.log(callback) 
})
```

## Queries Parameters

* `id`: Set the CVE id
