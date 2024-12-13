# tradestation-api-js-wrapper

Wrapper around most of the Tradestation API. This project includes a full OAuth layer.

## Key Features:
- Comprehensive wrapper for the Tradestation API
- Built-in OAuth authentication mechanism
- Classes-based structure for easy usage

## Main Files:
### ts.js
Entry point for non-OAuth related endpoints. Use this file for accessing various API functions.

### authentication.js
Entry point for OAuth-related functionalities.

## Usage Examples:

```Javascript
var tsAuth = new TSAuthentication();
// For refreshing the token.
tsAuth.triggerRefresh();

// For getting a new access token
tsAuth.getNewAccessToken();
```

This repository provides a convenient JavaScript wrapper for interacting with the Tradestation API, simplifying the process of integrating Tradestation services into your applications.
