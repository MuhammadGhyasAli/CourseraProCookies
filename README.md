# CourseraProCookies
## cookies.json

The `cookies.json` file contains exported browser cookies required for authenticated access to Coursera resources. This file is typically generated using browser extensions or manual export tools.

### Usage

1. Export your Coursera cookies from your browser as a JSON file.
2. Save the exported file as `cookies.json` in this repository.
3. Use this file with scripts or tools that require authenticated requests to Coursera.

#### Step-by-step: Exporting Cookies with Cookie Editor

1. Visit [Cookie Editor extension page](https://chromewebstore.google.com/detail/cookie-editor/hlkenndednhfkekhgcdicdfddnkalmdm) in your browser.
2. Install the Cookie Editor extension.
3. Open Coursera in your browser.
4. Click the Cookie Editor extension icon.
5. Use the extension's export feature to save cookies as a JSON file.
6. Copy code from `cookies.json` and paste on import

### Security

- **Do not share your `cookies.json` file publicly.** It contains sensitive authentication data.
- Remove or rotate cookies if you suspect they are compromised.

### Example

```json
[
    {
        "domain": ".coursera.org",
        "name": "CAUTH",
        "value": "your_auth_token",
        "path": "/",
        "secure": true,
        "httpOnly": true,
        "expirationDate": 1712345678
    }
]
```

### References

- [Coursera Cookie Export Guide](https://github.com/coursera-dl/coursera-dl#obtaining-cookies)
- [How to Export Cookies (Chrome)](https://chrome.google.com/webstore/detail/cookies-exportimport/jcbpglgkjjjgkdfcpbfpmmjcfpjjkfjc)
- [Cookie Editor Extension](https://chromewebstore.google.com/detail/cookie-editor/hlkenndednhfkekhgcdicdfddnkalmdm)
