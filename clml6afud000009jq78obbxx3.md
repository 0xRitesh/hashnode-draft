---
title: "FETCH API in JavaScript."
datePublished: Fri Sep 15 2023 22:30:11 GMT+0000 (Coordinated Universal Time)
cuid: clml6afud000009jq78obbxx3
slug: fetch-api-in-javascript
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1694766548221/77ae4a8a-b656-46f7-b1cb-77331af81f2a.png
tags: javascript

---

Fetch API in a nutshell, I have used it many times in small-scale projects. The JSON part can be irritating though but it is still worth using it!

## FETCH API

Fetch API is used to make HTTP requests, It has more power and flexibility as compared to AJAX. Fetch returns a Promise as the requests get loaded. The first parameter it takes is the URL we want to request.

```typescript
fetch("https://jsonplaceholder.hashnode.com/posts/2")
.then(res=>
})
.catch(err=>{
})
```

## USAGE

We can pass an object as a second parameter with additional options as a property. I like the method, body, headers, etc.

```typescript

const obj = {

method "POST",

body: JSON.stringify({name:"riteshkumar"}), 
headers : {
'Content-Type' : 'application/json'
}
}
fetch("https://jsonplaceholder.hashnode.com/posts/2",obj)
.then(res=>{
})
.catch(err=>{
})
```

---

Once the request is fulfilled then you have two options either to convert the response into text or JSON. We can do that by using text() and JSON () methods on the returned response. now again, text() and json() also returns a promise.

Conclusion: The fetch method can be intimidating to use at first but as you practice more you will grow to like it more and more, the most useful thing is it can solve your long data fetching very easily. I hope that by reading the blogs you grow to like the fetch method more. You will find it more interesting and helpful with that I want to end this blog.

**Thanks for reading the article!**

Wishing you a great JavaScript day ahead!