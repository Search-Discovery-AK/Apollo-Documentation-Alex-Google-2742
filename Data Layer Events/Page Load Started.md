# Page Load Started

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ page_data: null });  // Clear the previous page_data object.
dataLayer.push({
  "event": "page_view",
  "apollo_event": "Page Load Started",
    "page_data": {
        "country": "<country>",
        "language": "<language>",
        "page_location": "<page_location>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|country|string|The country the site is associated with.||||||||
|language|string|The language of the current page, usually pulled from the &lt;html&gt; tag lang attribute.||||||||
|page_location|string|The url of the page currently being viewed.||||||||




