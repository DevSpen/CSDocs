# @url

Encodes/decodes/baldifies a URL.

### Usage

```text
@url[type=encode/decode/baldify, URL]
```

#### Breakdown

`type` - The action to perform on a URL. Options:

* `encode` - Encodes a URL \(e.g. `;` becomes `%3B`\).
* `decode` - Decodes a URL \(e.g. `%3B` becomes `;`\)
* `baldify` - Baldifies a URL. This means the URL is returned without any `https://`, `www.`, `http://` at the beginning.

`URL` - The URL to perform the effect on.

### Examples

```text
@url[type=decode, https://google.com/search?q=%3B%5B%5D%5C
```

```text
@url[type=encode, https://google.com/search?q=;[]\]
```

```diff
@url[type=baldify, https://google.com/search?q=%3B%5B%5D%5C]
```

