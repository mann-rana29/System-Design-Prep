# URL Shortener

`Bit.ly` is a URL shortening service that converts long URLs into shorter links. For eg -
``` 
www.example.com/users/23/is/blab..  -->  www.bit.ly/GH234
```

## Requirements

#### Functional Requirements
- Create short URL from a long URL
- New URL should always redirect to the original URL
- Optionally support an expiration time

#### Non - Functional Requirements
- Low latency on redirects
- High Availability, Eventual Consistency
- Ensure Uniqueness of short URL
- Scale to support 100M Daily active users(DAU) and 1B URLs

## Core Entities
- Original url
- Short url
- User

## API
- Shorten a URL
  ```
    POST /urls -> shortUrl
    {
        originalUrl,
        expirationTime (Optional) ?
    }
    ```

- Redirect a URL
    ```
    GET {shortUrl} -> Redirect to Original URL
    ```
