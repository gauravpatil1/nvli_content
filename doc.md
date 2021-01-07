---
title: Indian Culture APIs v1.0
language_tabs:
  - shell: Shell
  - http: HTTP
  - javascript: JavaScript
  - ruby: Ruby
  - python: Python
  - php: PHP
  - java: Java
  - go: Go
toc_footers: []
includes: []
search: true
highlight_theme: darkula
headingLevel: 2

---

<!-- Generator: Widdershins v4.0.1 -->

<h1 id="indian-culture-apis">Indian Culture APIs v1.0</h1>

> Scroll down for code samples, example requests and responses. Select a language for code samples from the tabs above or the mobile navigation menu.

Base URLs:

* <a href="https://indianculture.gov.in/">https://indianculture.gov.in/</a>

<h1 id="indian-culture-apis-slider-images">Slider Images</h1>

## SliderImagesListinEnglish

<a id="opIdSliderImagesListinEnglish"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/rest/home-page-slider

```

```http
GET https://indianculture.gov.in/rest/home-page-slider HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/rest/home-page-slider',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/rest/home-page-slider',
  params: {
  }

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/rest/home-page-slider')

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/rest/home-page-slider', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/rest/home-page-slider");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/rest/home-page-slider", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /rest/home-page-slider`

*Slider Images List in English*

<h3 id="sliderimageslistinenglish-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## SliderImagesListinHindi

<a id="opIdSliderImagesListinHindi"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/hi/rest/home-page-slider

```

```http
GET https://indianculture.gov.in/hi/rest/home-page-slider HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/hi/rest/home-page-slider',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/hi/rest/home-page-slider',
  params: {
  }

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/hi/rest/home-page-slider')

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/hi/rest/home-page-slider', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/hi/rest/home-page-slider");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/hi/rest/home-page-slider", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /hi/rest/home-page-slider`

*Slider Images List in Hindi*

<h3 id="sliderimageslistinhindi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

<h1 id="indian-culture-apis-external-links">External Links</h1>

## ExternalLinksListinEnglish

<a id="opIdExternalLinksListinEnglish"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/rest/externalLinks

```

```http
GET https://indianculture.gov.in/rest/externalLinks HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/rest/externalLinks',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/rest/externalLinks',
  params: {
  }

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/rest/externalLinks')

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/rest/externalLinks', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/rest/externalLinks");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/rest/externalLinks", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /rest/externalLinks`

*External Links List in English*

<h3 id="externallinkslistinenglish-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## ExternalLinksListinHindi

<a id="opIdExternalLinksListinHindi"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/hi/rest/externalLinks

```

```http
GET https://indianculture.gov.in/hi/rest/externalLinks HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/hi/rest/externalLinks',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/hi/rest/externalLinks',
  params: {
  }

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/hi/rest/externalLinks')

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/hi/rest/externalLinks', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/hi/rest/externalLinks");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/hi/rest/externalLinks", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /hi/rest/externalLinks`

*External Links List in Hindi*

<h3 id="externallinkslistinhindi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

<h1 id="indian-culture-apis-did-you-know">Did You Know</h1>

## DidYouKnowDetailsinEnglish

<a id="opIdDidYouKnowDetailsinEnglish"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/rest/did_you_know

```

```http
GET https://indianculture.gov.in/rest/did_you_know HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/rest/did_you_know',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/rest/did_you_know',
  params: {
  }

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/rest/did_you_know')

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/rest/did_you_know', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/rest/did_you_know");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/rest/did_you_know", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /rest/did_you_know`

*Did You Know Details in English*

<h3 id="didyouknowdetailsinenglish-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## DidYouKnowDetailsinHindi

<a id="opIdDidYouKnowDetailsinHindi"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/hi/rest/did_you_know

```

```http
GET https://indianculture.gov.in/hi/rest/did_you_know HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/hi/rest/did_you_know',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/hi/rest/did_you_know',
  params: {
  }

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/hi/rest/did_you_know')

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/hi/rest/did_you_know', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/hi/rest/did_you_know");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/hi/rest/did_you_know", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /hi/rest/did_you_know`

*Did You Know Details in Hindi*

<h3 id="didyouknowdetailsinhindi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

<h1 id="indian-culture-apis-full-search">Full Search</h1>

## FullSearchListinEnglish

<a id="opIdFullSearchListinEnglish"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/rest-v1/indian-culture-repositories?page=0&search_api_fulltext=string

```

```http
GET https://indianculture.gov.in/rest-v1/indian-culture-repositories?page=0&search_api_fulltext=string HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/rest-v1/indian-culture-repositories?page=0&search_api_fulltext=string',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/rest-v1/indian-culture-repositories',
  params: {
  'page' => 'integer(int32)',
'search_api_fulltext' => 'string'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/rest-v1/indian-culture-repositories', params={
  'page': '0',  'search_api_fulltext': 'string'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/rest-v1/indian-culture-repositories', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/rest-v1/indian-culture-repositories?page=0&search_api_fulltext=string");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/rest-v1/indian-culture-repositories", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /rest-v1/indian-culture-repositories`

*Full Search List in English*

<h3 id="fullsearchlistinenglish-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|
|search_api_fulltext|query|string|true|A string describing text to be searched in that list|

<h3 id="fullsearchlistinenglish-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## FullSearchListinHindi

<a id="opIdFullSearchListinHindi"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/hi/rest-v1/indian-culture-repositories?page=0&search_api_fulltext=string

```

```http
GET https://indianculture.gov.in/hi/rest-v1/indian-culture-repositories?page=0&search_api_fulltext=string HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/hi/rest-v1/indian-culture-repositories?page=0&search_api_fulltext=string',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/hi/rest-v1/indian-culture-repositories',
  params: {
  'page' => 'integer(int32)',
'search_api_fulltext' => 'string'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/hi/rest-v1/indian-culture-repositories', params={
  'page': '0',  'search_api_fulltext': 'string'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/hi/rest-v1/indian-culture-repositories', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/hi/rest-v1/indian-culture-repositories?page=0&search_api_fulltext=string");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/hi/rest-v1/indian-culture-repositories", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /hi/rest-v1/indian-culture-repositories`

*Full Search List in Hindi*

<h3 id="fullsearchlistinhindi-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|
|search_api_fulltext|query|string|true|A string describing text to be searched in that list|

<h3 id="fullsearchlistinhindi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

<h1 id="indian-culture-apis-audio">Audio</h1>

## AudioListinEnglish

<a id="opIdAudioListinEnglish"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/rest-v1/audios?page=0&search_api_fulltext=string

```

```http
GET https://indianculture.gov.in/rest-v1/audios?page=0&search_api_fulltext=string HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/rest-v1/audios?page=0&search_api_fulltext=string',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/rest-v1/audios',
  params: {
  'page' => 'integer(int32)',
'search_api_fulltext' => 'string'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/rest-v1/audios', params={
  'page': '0',  'search_api_fulltext': 'string'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/rest-v1/audios', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/rest-v1/audios?page=0&search_api_fulltext=string");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/rest-v1/audios", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /rest-v1/audios`

*Audio List in English*

<h3 id="audiolistinenglish-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|
|search_api_fulltext|query|string|true|A string describing text to be searched in that list|

<h3 id="audiolistinenglish-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## AudioListinHindi

<a id="opIdAudioListinHindi"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/hi/rest-v1/audios?page=0&search_api_fulltext=string

```

```http
GET https://indianculture.gov.in/hi/rest-v1/audios?page=0&search_api_fulltext=string HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/hi/rest-v1/audios?page=0&search_api_fulltext=string',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/hi/rest-v1/audios',
  params: {
  'page' => 'integer(int32)',
'search_api_fulltext' => 'string'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/hi/rest-v1/audios', params={
  'page': '0',  'search_api_fulltext': 'string'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/hi/rest-v1/audios', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/hi/rest-v1/audios?page=0&search_api_fulltext=string");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/hi/rest-v1/audios", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /hi/rest-v1/audios`

*Audio List in Hindi*

<h3 id="audiolistinhindi-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|
|search_api_fulltext|query|string|true|A string describing text to be searched in that list|

<h3 id="audiolistinhindi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

<h1 id="indian-culture-apis-snippet">Snippet</h1>

## SnippetListinEnglish

<a id="opIdSnippetListinEnglish"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/rest-v1/snippets?page=0

```

```http
GET https://indianculture.gov.in/rest-v1/snippets?page=0 HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/rest-v1/snippets?page=0',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/rest-v1/snippets',
  params: {
  'page' => 'integer(int32)'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/rest-v1/snippets', params={
  'page': '0'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/rest-v1/snippets', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/rest-v1/snippets?page=0");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/rest-v1/snippets", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /rest-v1/snippets`

*Snippet List in English*

<h3 id="snippetlistinenglish-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|

<h3 id="snippetlistinenglish-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## SnippetListinHindi

<a id="opIdSnippetListinHindi"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/hi/rest-v1/snippets?page=0

```

```http
GET https://indianculture.gov.in/hi/rest-v1/snippets?page=0 HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/hi/rest-v1/snippets?page=0',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/hi/rest-v1/snippets',
  params: {
  'page' => 'integer(int32)'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/hi/rest-v1/snippets', params={
  'page': '0'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/hi/rest-v1/snippets', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/hi/rest-v1/snippets?page=0");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/hi/rest-v1/snippets", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /hi/rest-v1/snippets`

*Snippet List in Hindi*

<h3 id="snippetlistinhindi-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|

<h3 id="snippetlistinhindi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

<h1 id="indian-culture-apis-research-papers">Research Papers</h1>

## ResearchPapersListinEnglish

<a id="opIdResearchPapersListinEnglish"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/rest-v1/research-papers?page=0&search_api_fulltext=string

```

```http
GET https://indianculture.gov.in/rest-v1/research-papers?page=0&search_api_fulltext=string HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/rest-v1/research-papers?page=0&search_api_fulltext=string',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/rest-v1/research-papers',
  params: {
  'page' => 'integer(int32)',
'search_api_fulltext' => 'string'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/rest-v1/research-papers', params={
  'page': '0',  'search_api_fulltext': 'string'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/rest-v1/research-papers', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/rest-v1/research-papers?page=0&search_api_fulltext=string");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/rest-v1/research-papers", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /rest-v1/research-papers`

*Research Papers List in English*

<h3 id="researchpaperslistinenglish-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|
|search_api_fulltext|query|string|true|A string describing text to be searched in that list|

<h3 id="researchpaperslistinenglish-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## ResearchPapersListinHindi

<a id="opIdResearchPapersListinHindi"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/hi/rest-v1/research-papers?page=0&search_api_fulltext=string

```

```http
GET https://indianculture.gov.in/hi/rest-v1/research-papers?page=0&search_api_fulltext=string HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/hi/rest-v1/research-papers?page=0&search_api_fulltext=string',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/hi/rest-v1/research-papers',
  params: {
  'page' => 'integer(int32)',
'search_api_fulltext' => 'string'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/hi/rest-v1/research-papers', params={
  'page': '0',  'search_api_fulltext': 'string'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/hi/rest-v1/research-papers', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/hi/rest-v1/research-papers?page=0&search_api_fulltext=string");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/hi/rest-v1/research-papers", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /hi/rest-v1/research-papers`

*Research Papers List in Hindi*

<h3 id="researchpaperslistinhindi-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|
|search_api_fulltext|query|string|true|A string describing text to be searched in that list|

<h3 id="researchpaperslistinhindi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

<h1 id="indian-culture-apis-rare-books">Rare Books</h1>

## RareBooksListinEnglish

<a id="opIdRareBooksListinEnglish"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/rest-v1/rarebooks?page=0&search_api_fulltext=string

```

```http
GET https://indianculture.gov.in/rest-v1/rarebooks?page=0&search_api_fulltext=string HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/rest-v1/rarebooks?page=0&search_api_fulltext=string',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/rest-v1/rarebooks',
  params: {
  'page' => 'integer(int32)',
'search_api_fulltext' => 'string'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/rest-v1/rarebooks', params={
  'page': '0',  'search_api_fulltext': 'string'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/rest-v1/rarebooks', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/rest-v1/rarebooks?page=0&search_api_fulltext=string");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/rest-v1/rarebooks", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /rest-v1/rarebooks`

*Rare Books List in English*

<h3 id="rarebookslistinenglish-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|
|search_api_fulltext|query|string|true|A string describing text to be searched in that list|

<h3 id="rarebookslistinenglish-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## RareBooksListinHindi

<a id="opIdRareBooksListinHindi"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/hi/rest-v1/rarebooks?page=0&search_api_fulltext=string

```

```http
GET https://indianculture.gov.in/hi/rest-v1/rarebooks?page=0&search_api_fulltext=string HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/hi/rest-v1/rarebooks?page=0&search_api_fulltext=string',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/hi/rest-v1/rarebooks',
  params: {
  'page' => 'integer(int32)',
'search_api_fulltext' => 'string'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/hi/rest-v1/rarebooks', params={
  'page': '0',  'search_api_fulltext': 'string'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/hi/rest-v1/rarebooks', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/hi/rest-v1/rarebooks?page=0&search_api_fulltext=string");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/hi/rest-v1/rarebooks", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /hi/rest-v1/rarebooks`

*Rare Books List in Hindi*

<h3 id="rarebookslistinhindi-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|
|search_api_fulltext|query|string|true|A string describing text to be searched in that list|

<h3 id="rarebookslistinhindi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

<h1 id="indian-culture-apis-e-books">E-Books</h1>

## E-BooksListinEnglish

<a id="opIdE-BooksListinEnglish"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/rest-v1/ebooks?page=0&search_api_fulltext=string

```

```http
GET https://indianculture.gov.in/rest-v1/ebooks?page=0&search_api_fulltext=string HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/rest-v1/ebooks?page=0&search_api_fulltext=string',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/rest-v1/ebooks',
  params: {
  'page' => 'integer(int32)',
'search_api_fulltext' => 'string'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/rest-v1/ebooks', params={
  'page': '0',  'search_api_fulltext': 'string'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/rest-v1/ebooks', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/rest-v1/ebooks?page=0&search_api_fulltext=string");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/rest-v1/ebooks", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /rest-v1/ebooks`

*E-Books List in English*

<h3 id="e-bookslistinenglish-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|
|search_api_fulltext|query|string|true|A string describing text to be searched in that list|

<h3 id="e-bookslistinenglish-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## E-BooksListinHindi

<a id="opIdE-BooksListinHindi"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/hi/rest-v1/ebooks?page=0&search_api_fulltext=string

```

```http
GET https://indianculture.gov.in/hi/rest-v1/ebooks?page=0&search_api_fulltext=string HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/hi/rest-v1/ebooks?page=0&search_api_fulltext=string',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/hi/rest-v1/ebooks',
  params: {
  'page' => 'integer(int32)',
'search_api_fulltext' => 'string'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/hi/rest-v1/ebooks', params={
  'page': '0',  'search_api_fulltext': 'string'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/hi/rest-v1/ebooks', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/hi/rest-v1/ebooks?page=0&search_api_fulltext=string");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/hi/rest-v1/ebooks", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /hi/rest-v1/ebooks`

*E-Books List in Hindi*

<h3 id="e-bookslistinhindi-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|
|search_api_fulltext|query|string|true|A string describing text to be searched in that list|

<h3 id="e-bookslistinhindi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

<h1 id="indian-culture-apis-manuscripts">Manuscripts</h1>

## ManuscriptsListinEnglish

<a id="opIdManuscriptsListinEnglish"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/rest-v1/manuscripts?page=0&search_api_fulltext=string

```

```http
GET https://indianculture.gov.in/rest-v1/manuscripts?page=0&search_api_fulltext=string HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/rest-v1/manuscripts?page=0&search_api_fulltext=string',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/rest-v1/manuscripts',
  params: {
  'page' => 'integer(int32)',
'search_api_fulltext' => 'string'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/rest-v1/manuscripts', params={
  'page': '0',  'search_api_fulltext': 'string'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/rest-v1/manuscripts', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/rest-v1/manuscripts?page=0&search_api_fulltext=string");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/rest-v1/manuscripts", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /rest-v1/manuscripts`

*Manuscripts List in English*

<h3 id="manuscriptslistinenglish-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|
|search_api_fulltext|query|string|true|A string describing text to be searched in that list|

<h3 id="manuscriptslistinenglish-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## ManuscriptsListinHindi

<a id="opIdManuscriptsListinHindi"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/hi/rest-v1/manuscripts?page=0&search_api_fulltext=string

```

```http
GET https://indianculture.gov.in/hi/rest-v1/manuscripts?page=0&search_api_fulltext=string HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/hi/rest-v1/manuscripts?page=0&search_api_fulltext=string',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/hi/rest-v1/manuscripts',
  params: {
  'page' => 'integer(int32)',
'search_api_fulltext' => 'string'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/hi/rest-v1/manuscripts', params={
  'page': '0',  'search_api_fulltext': 'string'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/hi/rest-v1/manuscripts', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/hi/rest-v1/manuscripts?page=0&search_api_fulltext=string");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/hi/rest-v1/manuscripts", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /hi/rest-v1/manuscripts`

*Manuscripts List in Hindi*

<h3 id="manuscriptslistinhindi-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|
|search_api_fulltext|query|string|true|A string describing text to be searched in that list|

<h3 id="manuscriptslistinhindi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

<h1 id="indian-culture-apis-museums-collection">Museums Collection</h1>

## MuseumsCollectionListinEnglish

<a id="opIdMuseumsCollectionListinEnglish"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/rest-v1/museums-collection?page=0&search_api_fulltext=string

```

```http
GET https://indianculture.gov.in/rest-v1/museums-collection?page=0&search_api_fulltext=string HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/rest-v1/museums-collection?page=0&search_api_fulltext=string',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/rest-v1/museums-collection',
  params: {
  'page' => 'integer(int32)',
'search_api_fulltext' => 'string'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/rest-v1/museums-collection', params={
  'page': '0',  'search_api_fulltext': 'string'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/rest-v1/museums-collection', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/rest-v1/museums-collection?page=0&search_api_fulltext=string");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/rest-v1/museums-collection", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /rest-v1/museums-collection`

*Museums Collection List in English*

<h3 id="museumscollectionlistinenglish-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|
|search_api_fulltext|query|string|true|A string describing text to be searched in that list|

<h3 id="museumscollectionlistinenglish-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## MuseumsCollectionListinHindi

<a id="opIdMuseumsCollectionListinHindi"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/hi/rest-v1/museums-collection?page=0&search_api_fulltext=string

```

```http
GET https://indianculture.gov.in/hi/rest-v1/museums-collection?page=0&search_api_fulltext=string HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/hi/rest-v1/museums-collection?page=0&search_api_fulltext=string',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/hi/rest-v1/museums-collection',
  params: {
  'page' => 'integer(int32)',
'search_api_fulltext' => 'string'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/hi/rest-v1/museums-collection', params={
  'page': '0',  'search_api_fulltext': 'string'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/hi/rest-v1/museums-collection', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/hi/rest-v1/museums-collection?page=0&search_api_fulltext=string");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/hi/rest-v1/museums-collection", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /hi/rest-v1/museums-collection`

*Museums Collection List in Hindi*

<h3 id="museumscollectionlistinhindi-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|
|search_api_fulltext|query|string|true|A string describing text to be searched in that list|

<h3 id="museumscollectionlistinhindi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

<h1 id="indian-culture-apis-archives">Archives</h1>

## ArchivesListinEnglish

<a id="opIdArchivesListinEnglish"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/rest-v1/archive?page=0&search_api_fulltext=string

```

```http
GET https://indianculture.gov.in/rest-v1/archive?page=0&search_api_fulltext=string HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/rest-v1/archive?page=0&search_api_fulltext=string',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/rest-v1/archive',
  params: {
  'page' => 'integer(int32)',
'search_api_fulltext' => 'string'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/rest-v1/archive', params={
  'page': '0',  'search_api_fulltext': 'string'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/rest-v1/archive', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/rest-v1/archive?page=0&search_api_fulltext=string");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/rest-v1/archive", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /rest-v1/archive`

*Archives List in English*

<h3 id="archiveslistinenglish-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|
|search_api_fulltext|query|string|true|A string describing text to be searched in that list|

<h3 id="archiveslistinenglish-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## ArchivesListinHindi

<a id="opIdArchivesListinHindi"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/hi/rest-v1/archive?page=0&search_api_fulltext=string

```

```http
GET https://indianculture.gov.in/hi/rest-v1/archive?page=0&search_api_fulltext=string HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/hi/rest-v1/archive?page=0&search_api_fulltext=string',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/hi/rest-v1/archive',
  params: {
  'page' => 'integer(int32)',
'search_api_fulltext' => 'string'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/hi/rest-v1/archive', params={
  'page': '0',  'search_api_fulltext': 'string'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/hi/rest-v1/archive', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/hi/rest-v1/archive?page=0&search_api_fulltext=string");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/hi/rest-v1/archive", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /hi/rest-v1/archive`

*Archives List in Hindi*

<h3 id="archiveslistinhindi-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|
|search_api_fulltext|query|string|true|A string describing text to be searched in that list|

<h3 id="archiveslistinhindi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

<h1 id="indian-culture-apis-photo-archives">Photo Archives</h1>

## PhotoArchivesListinEnglish

<a id="opIdPhotoArchivesListinEnglish"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/rest-v1/photo-archive?page=0&search_api_fulltext=string

```

```http
GET https://indianculture.gov.in/rest-v1/photo-archive?page=0&search_api_fulltext=string HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/rest-v1/photo-archive?page=0&search_api_fulltext=string',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/rest-v1/photo-archive',
  params: {
  'page' => 'integer(int32)',
'search_api_fulltext' => 'string'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/rest-v1/photo-archive', params={
  'page': '0',  'search_api_fulltext': 'string'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/rest-v1/photo-archive', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/rest-v1/photo-archive?page=0&search_api_fulltext=string");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/rest-v1/photo-archive", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /rest-v1/photo-archive`

*Photo Archives List in English*

<h3 id="photoarchiveslistinenglish-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|
|search_api_fulltext|query|string|true|A string describing text to be searched in that list|

<h3 id="photoarchiveslistinenglish-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## PhotoArchivesListinHindi

<a id="opIdPhotoArchivesListinHindi"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/hi/rest-v1/photo-archive?page=0&search_api_fulltext=string

```

```http
GET https://indianculture.gov.in/hi/rest-v1/photo-archive?page=0&search_api_fulltext=string HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/hi/rest-v1/photo-archive?page=0&search_api_fulltext=string',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/hi/rest-v1/photo-archive',
  params: {
  'page' => 'integer(int32)',
'search_api_fulltext' => 'string'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/hi/rest-v1/photo-archive', params={
  'page': '0',  'search_api_fulltext': 'string'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/hi/rest-v1/photo-archive', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/hi/rest-v1/photo-archive?page=0&search_api_fulltext=string");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/hi/rest-v1/photo-archive", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /hi/rest-v1/photo-archive`

*Photo Archives List in Hindi*

<h3 id="photoarchiveslistinhindi-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|
|search_api_fulltext|query|string|true|A string describing text to be searched in that list|

<h3 id="photoarchiveslistinhindi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

<h1 id="indian-culture-apis-gazetteers">Gazetteers</h1>

## GazetteersListinEnglish

<a id="opIdGazetteersListinEnglish"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/rest-v1/gazetteers?page=0&search_api_fulltext=string

```

```http
GET https://indianculture.gov.in/rest-v1/gazetteers?page=0&search_api_fulltext=string HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/rest-v1/gazetteers?page=0&search_api_fulltext=string',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/rest-v1/gazetteers',
  params: {
  'page' => 'integer(int32)',
'search_api_fulltext' => 'string'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/rest-v1/gazetteers', params={
  'page': '0',  'search_api_fulltext': 'string'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/rest-v1/gazetteers', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/rest-v1/gazetteers?page=0&search_api_fulltext=string");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/rest-v1/gazetteers", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /rest-v1/gazetteers`

*Gazetteers List in English*

<h3 id="gazetteerslistinenglish-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|
|search_api_fulltext|query|string|true|A string describing text to be searched in that list|

<h3 id="gazetteerslistinenglish-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## GazetteersListinHindi

<a id="opIdGazetteersListinHindi"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/hi/rest-v1/gazetteers?page=0&search_api_fulltext=string

```

```http
GET https://indianculture.gov.in/hi/rest-v1/gazetteers?page=0&search_api_fulltext=string HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/hi/rest-v1/gazetteers?page=0&search_api_fulltext=string',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/hi/rest-v1/gazetteers',
  params: {
  'page' => 'integer(int32)',
'search_api_fulltext' => 'string'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/hi/rest-v1/gazetteers', params={
  'page': '0',  'search_api_fulltext': 'string'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/hi/rest-v1/gazetteers', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/hi/rest-v1/gazetteers?page=0&search_api_fulltext=string");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/hi/rest-v1/gazetteers", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /hi/rest-v1/gazetteers`

*Gazetteers List in Hindi*

<h3 id="gazetteerslistinhindi-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|
|search_api_fulltext|query|string|true|A string describing text to be searched in that list|

<h3 id="gazetteerslistinhindi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

<h1 id="indian-culture-apis-union-catalogue">Union Catalogue</h1>

## UnionCatalogueListinEnglish

<a id="opIdUnionCatalogueListinEnglish"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/rest-v1/union-catalogue?page=0&search_api_fulltext=string

```

```http
GET https://indianculture.gov.in/rest-v1/union-catalogue?page=0&search_api_fulltext=string HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/rest-v1/union-catalogue?page=0&search_api_fulltext=string',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/rest-v1/union-catalogue',
  params: {
  'page' => 'integer(int32)',
'search_api_fulltext' => 'string'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/rest-v1/union-catalogue', params={
  'page': '0',  'search_api_fulltext': 'string'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/rest-v1/union-catalogue', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/rest-v1/union-catalogue?page=0&search_api_fulltext=string");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/rest-v1/union-catalogue", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /rest-v1/union-catalogue`

*Union Catalogue List in English*

<h3 id="unioncataloguelistinenglish-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|
|search_api_fulltext|query|string|true|A string describing text to be searched in that list|

<h3 id="unioncataloguelistinenglish-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## UnionCatalogueListinHindi

<a id="opIdUnionCatalogueListinHindi"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/hi/rest-v1/union-catalogue?page=0&search_api_fulltext=string

```

```http
GET https://indianculture.gov.in/hi/rest-v1/union-catalogue?page=0&search_api_fulltext=string HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/hi/rest-v1/union-catalogue?page=0&search_api_fulltext=string',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/hi/rest-v1/union-catalogue',
  params: {
  'page' => 'integer(int32)',
'search_api_fulltext' => 'string'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/hi/rest-v1/union-catalogue', params={
  'page': '0',  'search_api_fulltext': 'string'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/hi/rest-v1/union-catalogue', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/hi/rest-v1/union-catalogue?page=0&search_api_fulltext=string");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/hi/rest-v1/union-catalogue", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /hi/rest-v1/union-catalogue`

*Union Catalogue List in Hindi*

<h3 id="unioncataloguelistinhindi-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|
|search_api_fulltext|query|string|true|A string describing text to be searched in that list|

<h3 id="unioncataloguelistinhindi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

<h1 id="indian-culture-apis-indian-national-bibliography">Indian National Bibliography</h1>

## IndianNationalBibliographyListinEnglish

<a id="opIdIndianNationalBibliographyListinEnglish"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/rest-v1/catalogueinb?page=0&search_api_fulltext=string

```

```http
GET https://indianculture.gov.in/rest-v1/catalogueinb?page=0&search_api_fulltext=string HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/rest-v1/catalogueinb?page=0&search_api_fulltext=string',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/rest-v1/catalogueinb',
  params: {
  'page' => 'integer(int32)',
'search_api_fulltext' => 'string'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/rest-v1/catalogueinb', params={
  'page': '0',  'search_api_fulltext': 'string'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/rest-v1/catalogueinb', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/rest-v1/catalogueinb?page=0&search_api_fulltext=string");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/rest-v1/catalogueinb", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /rest-v1/catalogueinb`

*Indian National Bibliography List in English*

<h3 id="indiannationalbibliographylistinenglish-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|
|search_api_fulltext|query|string|true|A string describing text to be searched in that list|

<h3 id="indiannationalbibliographylistinenglish-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## IndianNationalBibliographyListinHindi

<a id="opIdIndianNationalBibliographyListinHindi"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/hi/rest-v1/catalogueinb?page=0&search_api_fulltext=string

```

```http
GET https://indianculture.gov.in/hi/rest-v1/catalogueinb?page=0&search_api_fulltext=string HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/hi/rest-v1/catalogueinb?page=0&search_api_fulltext=string',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/hi/rest-v1/catalogueinb',
  params: {
  'page' => 'integer(int32)',
'search_api_fulltext' => 'string'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/hi/rest-v1/catalogueinb', params={
  'page': '0',  'search_api_fulltext': 'string'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/hi/rest-v1/catalogueinb', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/hi/rest-v1/catalogueinb?page=0&search_api_fulltext=string");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/hi/rest-v1/catalogueinb", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /hi/rest-v1/catalogueinb`

*Indian National Bibliography List in Hindi*

<h3 id="indiannationalbibliographylistinhindi-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|
|search_api_fulltext|query|string|true|A string describing text to be searched in that list|

<h3 id="indiannationalbibliographylistinhindi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

<h1 id="indian-culture-apis-videos">Videos</h1>

## VideosListinEnglish

<a id="opIdVideosListinEnglish"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/rest-v1/videos?page=0&search_api_fulltext=string

```

```http
GET https://indianculture.gov.in/rest-v1/videos?page=0&search_api_fulltext=string HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/rest-v1/videos?page=0&search_api_fulltext=string',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/rest-v1/videos',
  params: {
  'page' => 'integer(int32)',
'search_api_fulltext' => 'string'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/rest-v1/videos', params={
  'page': '0',  'search_api_fulltext': 'string'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/rest-v1/videos', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/rest-v1/videos?page=0&search_api_fulltext=string");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/rest-v1/videos", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /rest-v1/videos`

*Videos List in English*

<h3 id="videoslistinenglish-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|
|search_api_fulltext|query|string|true|A string describing text to be searched in that list|

<h3 id="videoslistinenglish-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## VideosListinHindi

<a id="opIdVideosListinHindi"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/hi/rest-v1/videos?page=0&search_api_fulltext=string

```

```http
GET https://indianculture.gov.in/hi/rest-v1/videos?page=0&search_api_fulltext=string HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/hi/rest-v1/videos?page=0&search_api_fulltext=string',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/hi/rest-v1/videos',
  params: {
  'page' => 'integer(int32)',
'search_api_fulltext' => 'string'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/hi/rest-v1/videos', params={
  'page': '0',  'search_api_fulltext': 'string'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/hi/rest-v1/videos', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/hi/rest-v1/videos?page=0&search_api_fulltext=string");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/hi/rest-v1/videos", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /hi/rest-v1/videos`

*Videos List in Hindi*

<h3 id="videoslistinhindi-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|
|search_api_fulltext|query|string|true|A string describing text to be searched in that list|

<h3 id="videoslistinhindi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

<h1 id="indian-culture-apis-images">Images</h1>

## ImagesListinEnglish

<a id="opIdImagesListinEnglish"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/rest-v1/images?page=0&search_api_fulltext=string

```

```http
GET https://indianculture.gov.in/rest-v1/images?page=0&search_api_fulltext=string HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/rest-v1/images?page=0&search_api_fulltext=string',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/rest-v1/images',
  params: {
  'page' => 'integer(int32)',
'search_api_fulltext' => 'string'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/rest-v1/images', params={
  'page': '0',  'search_api_fulltext': 'string'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/rest-v1/images', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/rest-v1/images?page=0&search_api_fulltext=string");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/rest-v1/images", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /rest-v1/images`

*Images List in English*

<h3 id="imageslistinenglish-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|
|search_api_fulltext|query|string|true|A string describing text to be searched in that list|

<h3 id="imageslistinenglish-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## ImagesListinHindi

<a id="opIdImagesListinHindi"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/hi/rest-v1/images?page=0&search_api_fulltext=string

```

```http
GET https://indianculture.gov.in/hi/rest-v1/images?page=0&search_api_fulltext=string HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/hi/rest-v1/images?page=0&search_api_fulltext=string',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/hi/rest-v1/images',
  params: {
  'page' => 'integer(int32)',
'search_api_fulltext' => 'string'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/hi/rest-v1/images', params={
  'page': '0',  'search_api_fulltext': 'string'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/hi/rest-v1/images', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/hi/rest-v1/images?page=0&search_api_fulltext=string");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/hi/rest-v1/images", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /hi/rest-v1/images`

*Images List in Hindi*

<h3 id="imageslistinhindi-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|
|search_api_fulltext|query|string|true|A string describing text to be searched in that list|

<h3 id="imageslistinhindi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

<h1 id="indian-culture-apis-reports-and-proceedings">Reports and Proceedings</h1>

## ReportsandProceedingsListinEnglish

<a id="opIdReportsandProceedingsListinEnglish"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/rest-v1/reports-and-proceedings?page=0&search_api_fulltext=string

```

```http
GET https://indianculture.gov.in/rest-v1/reports-and-proceedings?page=0&search_api_fulltext=string HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/rest-v1/reports-and-proceedings?page=0&search_api_fulltext=string',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/rest-v1/reports-and-proceedings',
  params: {
  'page' => 'integer(int32)',
'search_api_fulltext' => 'string'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/rest-v1/reports-and-proceedings', params={
  'page': '0',  'search_api_fulltext': 'string'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/rest-v1/reports-and-proceedings', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/rest-v1/reports-and-proceedings?page=0&search_api_fulltext=string");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/rest-v1/reports-and-proceedings", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /rest-v1/reports-and-proceedings`

*Reports and Proceedings List in English*

<h3 id="reportsandproceedingslistinenglish-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|
|search_api_fulltext|query|string|true|A string describing text to be searched in that list|

<h3 id="reportsandproceedingslistinenglish-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## ReportsandProceedingsListinHindi

<a id="opIdReportsandProceedingsListinHindi"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/hi/rest-v1/reports-and-proceedings?page=0&search_api_fulltext=string

```

```http
GET https://indianculture.gov.in/hi/rest-v1/reports-and-proceedings?page=0&search_api_fulltext=string HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/hi/rest-v1/reports-and-proceedings?page=0&search_api_fulltext=string',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/hi/rest-v1/reports-and-proceedings',
  params: {
  'page' => 'integer(int32)',
'search_api_fulltext' => 'string'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/hi/rest-v1/reports-and-proceedings', params={
  'page': '0',  'search_api_fulltext': 'string'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/hi/rest-v1/reports-and-proceedings', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/hi/rest-v1/reports-and-proceedings?page=0&search_api_fulltext=string");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/hi/rest-v1/reports-and-proceedings", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /hi/rest-v1/reports-and-proceedings`

*Reports and Proceedings List in Hindi*

<h3 id="reportsandproceedingslistinhindi-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|
|search_api_fulltext|query|string|true|A string describing text to be searched in that list|

<h3 id="reportsandproceedingslistinhindi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

<h1 id="indian-culture-apis-other-collections">Other Collections</h1>

## OtherCollectionsListinEnglish

<a id="opIdOtherCollectionsListinEnglish"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/rest-v1/other-collections?page=0&search_api_fulltext=string

```

```http
GET https://indianculture.gov.in/rest-v1/other-collections?page=0&search_api_fulltext=string HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/rest-v1/other-collections?page=0&search_api_fulltext=string',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/rest-v1/other-collections',
  params: {
  'page' => 'integer(int32)',
'search_api_fulltext' => 'string'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/rest-v1/other-collections', params={
  'page': '0',  'search_api_fulltext': 'string'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/rest-v1/other-collections', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/rest-v1/other-collections?page=0&search_api_fulltext=string");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/rest-v1/other-collections", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /rest-v1/other-collections`

*Other Collections List in English*

<h3 id="othercollectionslistinenglish-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|
|search_api_fulltext|query|string|true|A string describing text to be searched in that list|

<h3 id="othercollectionslistinenglish-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## OtherCollectionsListinHindi

<a id="opIdOtherCollectionsListinHindi"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/hi/rest-v1/other-collections?page=0&search_api_fulltext=string

```

```http
GET https://indianculture.gov.in/hi/rest-v1/other-collections?page=0&search_api_fulltext=string HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/hi/rest-v1/other-collections?page=0&search_api_fulltext=string',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/hi/rest-v1/other-collections',
  params: {
  'page' => 'integer(int32)',
'search_api_fulltext' => 'string'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/hi/rest-v1/other-collections', params={
  'page': '0',  'search_api_fulltext': 'string'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/hi/rest-v1/other-collections', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/hi/rest-v1/other-collections?page=0&search_api_fulltext=string");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/hi/rest-v1/other-collections", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /hi/rest-v1/other-collections`

*Other Collections List in Hindi*

<h3 id="othercollectionslistinhindi-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|
|search_api_fulltext|query|string|true|A string describing text to be searched in that list|

<h3 id="othercollectionslistinhindi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

<h1 id="indian-culture-apis-stories">Stories</h1>

## StoriesListinEnglish

<a id="opIdStoriesListinEnglish"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/rest-v1/stories?page=0&search_api_fulltext=string

```

```http
GET https://indianculture.gov.in/rest-v1/stories?page=0&search_api_fulltext=string HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/rest-v1/stories?page=0&search_api_fulltext=string',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/rest-v1/stories',
  params: {
  'page' => 'integer(int32)',
'search_api_fulltext' => 'string'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/rest-v1/stories', params={
  'page': '0',  'search_api_fulltext': 'string'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/rest-v1/stories', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/rest-v1/stories?page=0&search_api_fulltext=string");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/rest-v1/stories", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /rest-v1/stories`

*Stories List in English*

<h3 id="storieslistinenglish-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|
|search_api_fulltext|query|string|true|A string describing text to be searched in that list|

<h3 id="storieslistinenglish-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## StoriesListinHindi

<a id="opIdStoriesListinHindi"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/hi/rest-v1/stories?page=0&search_api_fulltext=string

```

```http
GET https://indianculture.gov.in/hi/rest-v1/stories?page=0&search_api_fulltext=string HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/hi/rest-v1/stories?page=0&search_api_fulltext=string',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/hi/rest-v1/stories',
  params: {
  'page' => 'integer(int32)',
'search_api_fulltext' => 'string'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/hi/rest-v1/stories', params={
  'page': '0',  'search_api_fulltext': 'string'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/hi/rest-v1/stories', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/hi/rest-v1/stories?page=0&search_api_fulltext=string");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/hi/rest-v1/stories", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /hi/rest-v1/stories`

*Stories List in Hindi*

<h3 id="storieslistinhindi-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|
|search_api_fulltext|query|string|true|A string describing text to be searched in that list|

<h3 id="storieslistinhindi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

<h1 id="indian-culture-apis-moc-organisations">MoC Organisations</h1>

## MoCOrganisationsListinEnglish

<a id="opIdMoCOrganisationsListinEnglish"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/rest-v1/moc-organisations?page=0&search_api_fulltext=string

```

```http
GET https://indianculture.gov.in/rest-v1/moc-organisations?page=0&search_api_fulltext=string HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/rest-v1/moc-organisations?page=0&search_api_fulltext=string',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/rest-v1/moc-organisations',
  params: {
  'page' => 'integer(int32)',
'search_api_fulltext' => 'string'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/rest-v1/moc-organisations', params={
  'page': '0',  'search_api_fulltext': 'string'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/rest-v1/moc-organisations', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/rest-v1/moc-organisations?page=0&search_api_fulltext=string");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/rest-v1/moc-organisations", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /rest-v1/moc-organisations`

*MoC Organisations List in English*

<h3 id="mocorganisationslistinenglish-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|
|search_api_fulltext|query|string|true|A string describing text to be searched in that list|

<h3 id="mocorganisationslistinenglish-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## MoCOrganisationsListinHindi

<a id="opIdMoCOrganisationsListinHindi"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/hi/rest-v1/moc-organisations?page=0&search_api_fulltext=string

```

```http
GET https://indianculture.gov.in/hi/rest-v1/moc-organisations?page=0&search_api_fulltext=string HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/hi/rest-v1/moc-organisations?page=0&search_api_fulltext=string',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/hi/rest-v1/moc-organisations',
  params: {
  'page' => 'integer(int32)',
'search_api_fulltext' => 'string'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/hi/rest-v1/moc-organisations', params={
  'page': '0',  'search_api_fulltext': 'string'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/hi/rest-v1/moc-organisations', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/hi/rest-v1/moc-organisations?page=0&search_api_fulltext=string");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/hi/rest-v1/moc-organisations", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /hi/rest-v1/moc-organisations`

*MoC Organisations List in Hindi*

<h3 id="mocorganisationslistinhindi-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|
|search_api_fulltext|query|string|true|A string describing text to be searched in that list|

<h3 id="mocorganisationslistinhindi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

<h1 id="indian-culture-apis-museum-paintings">Museum Paintings</h1>

## MuseumPaintingsListinEnglish

<a id="opIdMuseumPaintingsListinEnglish"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/rest-v1/painting-collections/museum-paintings?page=0&search_api_fulltext=string

```

```http
GET https://indianculture.gov.in/rest-v1/painting-collections/museum-paintings?page=0&search_api_fulltext=string HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/rest-v1/painting-collections/museum-paintings?page=0&search_api_fulltext=string',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/rest-v1/painting-collections/museum-paintings',
  params: {
  'page' => 'integer(int32)',
'search_api_fulltext' => 'string'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/rest-v1/painting-collections/museum-paintings', params={
  'page': '0',  'search_api_fulltext': 'string'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/rest-v1/painting-collections/museum-paintings', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/rest-v1/painting-collections/museum-paintings?page=0&search_api_fulltext=string");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/rest-v1/painting-collections/museum-paintings", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /rest-v1/painting-collections/museum-paintings`

*Museum Paintings List in English*

<h3 id="museumpaintingslistinenglish-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|
|search_api_fulltext|query|string|true|A string describing text to be searched in that list|

<h3 id="museumpaintingslistinenglish-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## MuseumPaintingsListinHindi

<a id="opIdMuseumPaintingsListinHindi"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/hi/rest-v1/painting-collections/museum-paintings?page=0&search_api_fulltext=string

```

```http
GET https://indianculture.gov.in/hi/rest-v1/painting-collections/museum-paintings?page=0&search_api_fulltext=string HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/hi/rest-v1/painting-collections/museum-paintings?page=0&search_api_fulltext=string',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/hi/rest-v1/painting-collections/museum-paintings',
  params: {
  'page' => 'integer(int32)',
'search_api_fulltext' => 'string'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/hi/rest-v1/painting-collections/museum-paintings', params={
  'page': '0',  'search_api_fulltext': 'string'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/hi/rest-v1/painting-collections/museum-paintings', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/hi/rest-v1/painting-collections/museum-paintings?page=0&search_api_fulltext=string");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/hi/rest-v1/painting-collections/museum-paintings", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /hi/rest-v1/painting-collections/museum-paintings`

*Museum Paintings List in Hindi*

<h3 id="museumpaintingslistinhindi-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|
|search_api_fulltext|query|string|true|A string describing text to be searched in that list|

<h3 id="museumpaintingslistinhindi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

<h1 id="indian-culture-apis-painting-portfolios">Painting Portfolios</h1>

## PaintingPortfoliosListinEnglish

<a id="opIdPaintingPortfoliosListinEnglish"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/rest-v1/paintings?page=0

```

```http
GET https://indianculture.gov.in/rest-v1/paintings?page=0 HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/rest-v1/paintings?page=0',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/rest-v1/paintings',
  params: {
  'page' => 'integer(int32)'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/rest-v1/paintings', params={
  'page': '0'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/rest-v1/paintings', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/rest-v1/paintings?page=0");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/rest-v1/paintings", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /rest-v1/paintings`

*Painting Portfolios List in English*

<h3 id="paintingportfolioslistinenglish-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|

<h3 id="paintingportfolioslistinenglish-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## PaintingPortfoliosListinHindi

<a id="opIdPaintingPortfoliosListinHindi"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/hi/rest-v1/paintings?page=0

```

```http
GET https://indianculture.gov.in/hi/rest-v1/paintings?page=0 HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/hi/rest-v1/paintings?page=0',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/hi/rest-v1/paintings',
  params: {
  'page' => 'integer(int32)'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/hi/rest-v1/paintings', params={
  'page': '0'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/hi/rest-v1/paintings', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/hi/rest-v1/paintings?page=0");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/hi/rest-v1/paintings", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /hi/rest-v1/paintings`

*Painting Portfolios List in Hindi*

<h3 id="paintingportfolioslistinhindi-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|

<h3 id="paintingportfolioslistinhindi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

<h1 id="indian-culture-apis-unesco">UNESCO</h1>

## UNESCOListinEnglish

<a id="opIdUNESCOListinEnglish"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/rest/unesco?page=0

```

```http
GET https://indianculture.gov.in/rest/unesco?page=0 HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/rest/unesco?page=0',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/rest/unesco',
  params: {
  'page' => 'integer(int32)'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/rest/unesco', params={
  'page': '0'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/rest/unesco', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/rest/unesco?page=0");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/rest/unesco", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /rest/unesco`

*UNESCO List in English*

<h3 id="unescolistinenglish-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|

<h3 id="unescolistinenglish-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## UNESCOListinHindi

<a id="opIdUNESCOListinHindi"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/hi/rest/unesco?page=0

```

```http
GET https://indianculture.gov.in/hi/rest/unesco?page=0 HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/hi/rest/unesco?page=0',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/hi/rest/unesco',
  params: {
  'page' => 'integer(int32)'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/hi/rest/unesco', params={
  'page': '0'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/hi/rest/unesco', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/hi/rest/unesco?page=0");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/hi/rest/unesco", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /hi/rest/unesco`

*UNESCO List in Hindi*

<h3 id="unescolistinhindi-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|

<h3 id="unescolistinhindi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## UNESCOSubCategoryListinEnglish

<a id="opIdUNESCOSubCategoryListinEnglish"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/rest-v1/unesco/heritage-site?page=0

```

```http
GET https://indianculture.gov.in/rest-v1/unesco/heritage-site?page=0 HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/rest-v1/unesco/heritage-site?page=0',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/rest-v1/unesco/heritage-site',
  params: {
  'page' => 'integer(int32)'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/rest-v1/unesco/heritage-site', params={
  'page': '0'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/rest-v1/unesco/heritage-site', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/rest-v1/unesco/heritage-site?page=0");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/rest-v1/unesco/heritage-site", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /rest-v1/unesco/heritage-site`

*UNESCO SubCategory List in English*

<h3 id="unescosubcategorylistinenglish-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|

<h3 id="unescosubcategorylistinenglish-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## UNESCOSubCategoryListinHindi

<a id="opIdUNESCOSubCategoryListinHindi"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/hi/rest-v1/unesco/heritage-site?page=0

```

```http
GET https://indianculture.gov.in/hi/rest-v1/unesco/heritage-site?page=0 HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/hi/rest-v1/unesco/heritage-site?page=0',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/hi/rest-v1/unesco/heritage-site',
  params: {
  'page' => 'integer(int32)'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/hi/rest-v1/unesco/heritage-site', params={
  'page': '0'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/hi/rest-v1/unesco/heritage-site', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/hi/rest-v1/unesco/heritage-site?page=0");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/hi/rest-v1/unesco/heritage-site", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /hi/rest-v1/unesco/heritage-site`

*UNESCO SubCategory List in Hindi*

<h3 id="unescosubcategorylistinhindi-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|

<h3 id="unescosubcategorylistinhindi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

<h1 id="indian-culture-apis-food-and-culture">Food and Culture</h1>

## FoodandCultureListinEnglish

<a id="opIdFoodandCultureListinEnglish"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/rest/food-and-culture?page=0

```

```http
GET https://indianculture.gov.in/rest/food-and-culture?page=0 HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/rest/food-and-culture?page=0',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/rest/food-and-culture',
  params: {
  'page' => 'integer(int32)'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/rest/food-and-culture', params={
  'page': '0'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/rest/food-and-culture', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/rest/food-and-culture?page=0");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/rest/food-and-culture", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /rest/food-and-culture`

*Food and Culture List in English*

<h3 id="foodandculturelistinenglish-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|

<h3 id="foodandculturelistinenglish-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## FoodandCultureListinHindi

<a id="opIdFoodandCultureListinHindi"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/hi/rest/food-and-culture?page=0

```

```http
GET https://indianculture.gov.in/hi/rest/food-and-culture?page=0 HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/hi/rest/food-and-culture?page=0',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/hi/rest/food-and-culture',
  params: {
  'page' => 'integer(int32)'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/hi/rest/food-and-culture', params={
  'page': '0'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/hi/rest/food-and-culture', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/hi/rest/food-and-culture?page=0");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/hi/rest/food-and-culture", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /hi/rest/food-and-culture`

*Food and Culture List in Hindi*

<h3 id="foodandculturelistinhindi-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|

<h3 id="foodandculturelistinhindi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## FoodandCultureSubCategoryListinEnglish

<a id="opIdFoodandCultureSubCategoryListinEnglish"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/rest-v1/food-and-culture/spices-and-herbs?page=0

```

```http
GET https://indianculture.gov.in/rest-v1/food-and-culture/spices-and-herbs?page=0 HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/rest-v1/food-and-culture/spices-and-herbs?page=0',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/rest-v1/food-and-culture/spices-and-herbs',
  params: {
  'page' => 'integer(int32)'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/rest-v1/food-and-culture/spices-and-herbs', params={
  'page': '0'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/rest-v1/food-and-culture/spices-and-herbs', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/rest-v1/food-and-culture/spices-and-herbs?page=0");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/rest-v1/food-and-culture/spices-and-herbs", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /rest-v1/food-and-culture/spices-and-herbs`

*Food and Culture SubCategory List in English*

<h3 id="foodandculturesubcategorylistinenglish-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|

<h3 id="foodandculturesubcategorylistinenglish-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## FoodandCultureSubCategoryListinHindi

<a id="opIdFoodandCultureSubCategoryListinHindi"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/hi/rest-v1/food-and-culture/spices-and-herbs?page=0

```

```http
GET https://indianculture.gov.in/hi/rest-v1/food-and-culture/spices-and-herbs?page=0 HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/hi/rest-v1/food-and-culture/spices-and-herbs?page=0',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/hi/rest-v1/food-and-culture/spices-and-herbs',
  params: {
  'page' => 'integer(int32)'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/hi/rest-v1/food-and-culture/spices-and-herbs', params={
  'page': '0'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/hi/rest-v1/food-and-culture/spices-and-herbs', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/hi/rest-v1/food-and-culture/spices-and-herbs?page=0");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/hi/rest-v1/food-and-culture/spices-and-herbs", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /hi/rest-v1/food-and-culture/spices-and-herbs`

*Food and Culture SubCategory List in Hindi*

<h3 id="foodandculturesubcategorylistinhindi-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|

<h3 id="foodandculturesubcategorylistinhindi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

<h1 id="indian-culture-apis-musical-instruments-of-india">Musical Instruments of India</h1>

## MusicalInstrumentsofIndiaListinEnglish

<a id="opIdMusicalInstrumentsofIndiaListinEnglish"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/rest/musical-instruments?page=0

```

```http
GET https://indianculture.gov.in/rest/musical-instruments?page=0 HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/rest/musical-instruments?page=0',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/rest/musical-instruments',
  params: {
  'page' => 'integer(int32)'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/rest/musical-instruments', params={
  'page': '0'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/rest/musical-instruments', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/rest/musical-instruments?page=0");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/rest/musical-instruments", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /rest/musical-instruments`

*Musical Instruments of India List in English*

<h3 id="musicalinstrumentsofindialistinenglish-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|

<h3 id="musicalinstrumentsofindialistinenglish-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## MusicalInstrumentsofIndiaListinHindi

<a id="opIdMusicalInstrumentsofIndiaListinHindi"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/hi/rest/musical-instruments?page=0

```

```http
GET https://indianculture.gov.in/hi/rest/musical-instruments?page=0 HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/hi/rest/musical-instruments?page=0',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/hi/rest/musical-instruments',
  params: {
  'page' => 'integer(int32)'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/hi/rest/musical-instruments', params={
  'page': '0'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/hi/rest/musical-instruments', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/hi/rest/musical-instruments?page=0");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/hi/rest/musical-instruments", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /hi/rest/musical-instruments`

*Musical Instruments of India List in Hindi*

<h3 id="musicalinstrumentsofindialistinhindi-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|

<h3 id="musicalinstrumentsofindialistinhindi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## MusicalInstrumentsofIndiaSubCategoryListinEnglish

<a id="opIdMusicalInstrumentsofIndiaSubCategoryListinEnglish"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/rest-v1/musical-instruments/avanaddha-vadya?page=0

```

```http
GET https://indianculture.gov.in/rest-v1/musical-instruments/avanaddha-vadya?page=0 HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/rest-v1/musical-instruments/avanaddha-vadya?page=0',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/rest-v1/musical-instruments/avanaddha-vadya',
  params: {
  'page' => 'integer(int32)'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/rest-v1/musical-instruments/avanaddha-vadya', params={
  'page': '0'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/rest-v1/musical-instruments/avanaddha-vadya', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/rest-v1/musical-instruments/avanaddha-vadya?page=0");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/rest-v1/musical-instruments/avanaddha-vadya", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /rest-v1/musical-instruments/avanaddha-vadya`

*Musical Instruments of India SubCategory List in English*

<h3 id="musicalinstrumentsofindiasubcategorylistinenglish-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|

<h3 id="musicalinstrumentsofindiasubcategorylistinenglish-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## MusicalInstrumentsofIndiaSubCategoryListinHindi

<a id="opIdMusicalInstrumentsofIndiaSubCategoryListinHindi"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/hi/rest-v1/musical-instruments/avanaddha-vadya?page=0

```

```http
GET https://indianculture.gov.in/hi/rest-v1/musical-instruments/avanaddha-vadya?page=0 HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/hi/rest-v1/musical-instruments/avanaddha-vadya?page=0',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/hi/rest-v1/musical-instruments/avanaddha-vadya',
  params: {
  'page' => 'integer(int32)'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/hi/rest-v1/musical-instruments/avanaddha-vadya', params={
  'page': '0'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/hi/rest-v1/musical-instruments/avanaddha-vadya', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/hi/rest-v1/musical-instruments/avanaddha-vadya?page=0");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/hi/rest-v1/musical-instruments/avanaddha-vadya", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /hi/rest-v1/musical-instruments/avanaddha-vadya`

*Musical Instruments of India SubCategory List in Hindi*

<h3 id="musicalinstrumentsofindiasubcategorylistinhindi-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|

<h3 id="musicalinstrumentsofindiasubcategorylistinhindi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

<h1 id="indian-culture-apis-intangible-cultural-heritage">Intangible Cultural Heritage</h1>

## IntangibleCulturalHeritageListinEnglish

<a id="opIdIntangibleCulturalHeritageListinEnglish"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/rest/intangible-cultural-heritage?page=0

```

```http
GET https://indianculture.gov.in/rest/intangible-cultural-heritage?page=0 HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/rest/intangible-cultural-heritage?page=0',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/rest/intangible-cultural-heritage',
  params: {
  'page' => 'integer(int32)'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/rest/intangible-cultural-heritage', params={
  'page': '0'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/rest/intangible-cultural-heritage', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/rest/intangible-cultural-heritage?page=0");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/rest/intangible-cultural-heritage", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /rest/intangible-cultural-heritage`

*Intangible Cultural Heritage List in English*

<h3 id="intangibleculturalheritagelistinenglish-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|

<h3 id="intangibleculturalheritagelistinenglish-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## IntangibleCulturalHeritageListinHindi

<a id="opIdIntangibleCulturalHeritageListinHindi"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/hi/rest/intangible-cultural-heritage?page=0

```

```http
GET https://indianculture.gov.in/hi/rest/intangible-cultural-heritage?page=0 HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/hi/rest/intangible-cultural-heritage?page=0',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/hi/rest/intangible-cultural-heritage',
  params: {
  'page' => 'integer(int32)'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/hi/rest/intangible-cultural-heritage', params={
  'page': '0'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/hi/rest/intangible-cultural-heritage', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/hi/rest/intangible-cultural-heritage?page=0");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/hi/rest/intangible-cultural-heritage", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /hi/rest/intangible-cultural-heritage`

*Intangible Cultural Heritage List in Hindi*

<h3 id="intangibleculturalheritagelistinhindi-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|

<h3 id="intangibleculturalheritagelistinhindi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## IntangibleCulturalHeritageSubCategoryListinEnglish

<a id="opIdIntangibleCulturalHeritageSubCategoryListinEnglish"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/rest-v1/intangible-cultural-heritage/performing-arts?page=0

```

```http
GET https://indianculture.gov.in/rest-v1/intangible-cultural-heritage/performing-arts?page=0 HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/rest-v1/intangible-cultural-heritage/performing-arts?page=0',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/rest-v1/intangible-cultural-heritage/performing-arts',
  params: {
  'page' => 'integer(int32)'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/rest-v1/intangible-cultural-heritage/performing-arts', params={
  'page': '0'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/rest-v1/intangible-cultural-heritage/performing-arts', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/rest-v1/intangible-cultural-heritage/performing-arts?page=0");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/rest-v1/intangible-cultural-heritage/performing-arts", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /rest-v1/intangible-cultural-heritage/performing-arts`

*Intangible Cultural Heritage SubCategory List in English*

<h3 id="intangibleculturalheritagesubcategorylistinenglish-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|

<h3 id="intangibleculturalheritagesubcategorylistinenglish-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## IntangibleCulturalHeritageSubCategoryListinHindi

<a id="opIdIntangibleCulturalHeritageSubCategoryListinHindi"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/hi/rest-v1/intangible-cultural-heritage/performing-arts?page=0

```

```http
GET https://indianculture.gov.in/hi/rest-v1/intangible-cultural-heritage/performing-arts?page=0 HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/hi/rest-v1/intangible-cultural-heritage/performing-arts?page=0',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/hi/rest-v1/intangible-cultural-heritage/performing-arts',
  params: {
  'page' => 'integer(int32)'
}

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/hi/rest-v1/intangible-cultural-heritage/performing-arts', params={
  'page': '0'
})

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/hi/rest-v1/intangible-cultural-heritage/performing-arts', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/hi/rest-v1/intangible-cultural-heritage/performing-arts?page=0");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/hi/rest-v1/intangible-cultural-heritage/performing-arts", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /hi/rest-v1/intangible-cultural-heritage/performing-arts`

*Intangible Cultural Heritage SubCategory List in Hindi*

<h3 id="intangibleculturalheritagesubcategorylistinhindi-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|page|query|integer(int32)|true|An integer describing page number to fetch a page in paginated list|

<h3 id="intangibleculturalheritagesubcategorylistinhindi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

<h1 id="indian-culture-apis-other-apis">Other APIs</h1>

## SearchResultDetailsinEnglish

<a id="opIdSearchResultDetailsinEnglish"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/rest/search-result/2544953

```

```http
GET https://indianculture.gov.in/rest/search-result/2544953 HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/rest/search-result/2544953',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/rest/search-result/2544953',
  params: {
  }

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/rest/search-result/2544953')

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/rest/search-result/2544953', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/rest/search-result/2544953");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/rest/search-result/2544953", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /rest/search-result/2544953`

*Search Result Details in English*

<h3 id="searchresultdetailsinenglish-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## SearchResultDetailsinHindi

<a id="opIdSearchResultDetailsinHindi"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/hi/rest/search-result/2544953

```

```http
GET https://indianculture.gov.in/hi/rest/search-result/2544953 HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/hi/rest/search-result/2544953',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/hi/rest/search-result/2544953',
  params: {
  }

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/hi/rest/search-result/2544953')

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/hi/rest/search-result/2544953', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/hi/rest/search-result/2544953");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/hi/rest/search-result/2544953", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /hi/rest/search-result/2544953`

*Search Result Details in Hindi*

<h3 id="searchresultdetailsinhindi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## CatalogueDetailsinEnglish

<a id="opIdCatalogueDetailsinEnglish"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/rest/bibliodata/1540833

```

```http
GET https://indianculture.gov.in/rest/bibliodata/1540833 HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/rest/bibliodata/1540833',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/rest/bibliodata/1540833',
  params: {
  }

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/rest/bibliodata/1540833')

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/rest/bibliodata/1540833', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/rest/bibliodata/1540833");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/rest/bibliodata/1540833", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /rest/bibliodata/1540833`

*Catalogue Details in English*

<h3 id="cataloguedetailsinenglish-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## CatalogueDetailsinHindi

<a id="opIdCatalogueDetailsinHindi"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/hi/rest/bibliodata/1540833

```

```http
GET https://indianculture.gov.in/hi/rest/bibliodata/1540833 HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/hi/rest/bibliodata/1540833',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/hi/rest/bibliodata/1540833',
  params: {
  }

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/hi/rest/bibliodata/1540833')

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/hi/rest/bibliodata/1540833', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/hi/rest/bibliodata/1540833");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/hi/rest/bibliodata/1540833", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /hi/rest/bibliodata/1540833`

*Catalogue Details in Hindi*

<h3 id="cataloguedetailsinhindi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## PaintingDetailsinEnglish

<a id="opIdPaintingDetailsinEnglish"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/rest/indianculture-paintings/2541490

```

```http
GET https://indianculture.gov.in/rest/indianculture-paintings/2541490 HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/rest/indianculture-paintings/2541490',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/rest/indianculture-paintings/2541490',
  params: {
  }

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/rest/indianculture-paintings/2541490')

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/rest/indianculture-paintings/2541490', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/rest/indianculture-paintings/2541490");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/rest/indianculture-paintings/2541490", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /rest/indianculture-paintings/2541490`

*Painting Details in English*

<h3 id="paintingdetailsinenglish-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## PaintingDetailsinHindi

<a id="opIdPaintingDetailsinHindi"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/hi/rest/indianculture-paintings/2541490

```

```http
GET https://indianculture.gov.in/hi/rest/indianculture-paintings/2541490 HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/hi/rest/indianculture-paintings/2541490',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/hi/rest/indianculture-paintings/2541490',
  params: {
  }

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/hi/rest/indianculture-paintings/2541490')

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/hi/rest/indianculture-paintings/2541490', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/hi/rest/indianculture-paintings/2541490");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/hi/rest/indianculture-paintings/2541490", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /hi/rest/indianculture-paintings/2541490`

*Painting Details in Hindi*

<h3 id="paintingdetailsinhindi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## UNESCODetailsinEnglish

<a id="opIdUNESCODetailsinEnglish"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/rest/unesco-records/2489638

```

```http
GET https://indianculture.gov.in/rest/unesco-records/2489638 HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/rest/unesco-records/2489638',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/rest/unesco-records/2489638',
  params: {
  }

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/rest/unesco-records/2489638')

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/rest/unesco-records/2489638', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/rest/unesco-records/2489638");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/rest/unesco-records/2489638", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /rest/unesco-records/2489638`

*UNESCO Details in English*

<h3 id="unescodetailsinenglish-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## UNESCODetailsinHindi

<a id="opIdUNESCODetailsinHindi"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/hi/rest/unesco-records/2489638

```

```http
GET https://indianculture.gov.in/hi/rest/unesco-records/2489638 HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/hi/rest/unesco-records/2489638',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/hi/rest/unesco-records/2489638',
  params: {
  }

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/hi/rest/unesco-records/2489638')

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/hi/rest/unesco-records/2489638', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/hi/rest/unesco-records/2489638");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/hi/rest/unesco-records/2489638", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /hi/rest/unesco-records/2489638`

*UNESCO Details in Hindi*

<h3 id="unescodetailsinhindi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## MusicalDetailsinEnglish

<a id="opIdMusicalDetailsinEnglish"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/rest/musical-instruments-records/2687930

```

```http
GET https://indianculture.gov.in/rest/musical-instruments-records/2687930 HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/rest/musical-instruments-records/2687930',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/rest/musical-instruments-records/2687930',
  params: {
  }

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/rest/musical-instruments-records/2687930')

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/rest/musical-instruments-records/2687930', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/rest/musical-instruments-records/2687930");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/rest/musical-instruments-records/2687930", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /rest/musical-instruments-records/2687930`

*Musical Details in English*

<h3 id="musicaldetailsinenglish-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## MusicalDetailsinHindi

<a id="opIdMusicalDetailsinHindi"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/hi/rest/musical-instruments-records/2687930

```

```http
GET https://indianculture.gov.in/hi/rest/musical-instruments-records/2687930 HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/hi/rest/musical-instruments-records/2687930',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/hi/rest/musical-instruments-records/2687930',
  params: {
  }

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/hi/rest/musical-instruments-records/2687930')

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/hi/rest/musical-instruments-records/2687930', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/hi/rest/musical-instruments-records/2687930");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/hi/rest/musical-instruments-records/2687930", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /hi/rest/musical-instruments-records/2687930`

*Musical Details in Hindi*

<h3 id="musicaldetailsinhindi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## IntangibleCulturalHeritageDetailsinEnglish

<a id="opIdIntangibleCulturalHeritageDetailsinEnglish"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/rest/ich-records/2688746

```

```http
GET https://indianculture.gov.in/rest/ich-records/2688746 HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/rest/ich-records/2688746',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/rest/ich-records/2688746',
  params: {
  }

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/rest/ich-records/2688746')

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/rest/ich-records/2688746', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/rest/ich-records/2688746");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/rest/ich-records/2688746", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /rest/ich-records/2688746`

*Intangible Cultural Heritage Details in English*

<h3 id="intangibleculturalheritagedetailsinenglish-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>

## IntangibleCulturalHeritageDetailsinHindi

<a id="opIdIntangibleCulturalHeritageDetailsinHindi"></a>

> Code samples

```shell
# You can also use wget
curl -X GET https://indianculture.gov.in/hi/rest/ich-records/2688746

```

```http
GET https://indianculture.gov.in/hi/rest/ich-records/2688746 HTTP/1.1
Host: indianculture.gov.in

```

```javascript

fetch('https://indianculture.gov.in/hi/rest/ich-records/2688746',
{
  method: 'GET'

})
.then(function(res) {
    return res.json();
}).then(function(body) {
    console.log(body);
});

```

```ruby
require 'rest-client'
require 'json'

result = RestClient.get 'https://indianculture.gov.in/hi/rest/ich-records/2688746',
  params: {
  }

p JSON.parse(result)

```

```python
import requests

r = requests.get('https://indianculture.gov.in/hi/rest/ich-records/2688746')

print(r.json())

```

```php
<?php

require 'vendor/autoload.php';

$client = new \GuzzleHttp\Client();

// Define array of request body.
$request_body = array();

try {
    $response = $client->request('GET','https://indianculture.gov.in/hi/rest/ich-records/2688746', array(
        'headers' => $headers,
        'json' => $request_body,
       )
    );
    print_r($response->getBody()->getContents());
 }
 catch (\GuzzleHttp\Exception\BadResponseException $e) {
    // handle exception or api errors.
    print_r($e->getMessage());
 }

 // ...

```

```java
URL obj = new URL("https://indianculture.gov.in/hi/rest/ich-records/2688746");
HttpURLConnection con = (HttpURLConnection) obj.openConnection();
con.setRequestMethod("GET");
int responseCode = con.getResponseCode();
BufferedReader in = new BufferedReader(
    new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer response = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    response.append(inputLine);
}
in.close();
System.out.println(response.toString());

```

```go
package main

import (
       "bytes"
       "net/http"
)

func main() {

    data := bytes.NewBuffer([]byte{jsonReq})
    req, err := http.NewRequest("GET", "https://indianculture.gov.in/hi/rest/ich-records/2688746", data)
    req.Header = headers

    client := &http.Client{}
    resp, err := client.Do(req)
    // ...
}

```

`GET /hi/rest/ich-records/2688746`

*Intangible Cultural Heritage Details in Hindi*

<h3 id="intangibleculturalheritagedetailsinhindi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|None|

<aside class="success">
This operation does not require authentication
</aside>
