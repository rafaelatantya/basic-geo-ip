# Geolocation Detection by IP
### Tool used :
1. CloudFlare IP info : https://www.cloudflare.com/cdn-cgi/trace
1. Free GeoIP : https://freegeoip.app
1. jQuery : https://code.jquery.com/

### How to Use
1. Download `geo-fetch.js`
1. Create HTML file and add this code<br/>
    * inside `<head>` tag
    Note : Replace `/path/to/geo-fetch-js` with your own
    ```html
    <script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
    <script src="/path/to/geo-fetch.js"></script>
    ```
    
    * Console log testing (the variable name is `userIPInfo`). You can change it by yourself
    ```javascript
    console.log(userIPInfo);
    ```
