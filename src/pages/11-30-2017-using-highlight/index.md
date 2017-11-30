---
path: "/using-highlight"
date: "2017-11-30T09:00:00.000Z"
title: "Using Highlight"
---

This is some beautiful code:

```javascript{1,4-6}
// In your gatsby-config.js
plugins: [
  {
    resolve: `gatsby-transformer-remark`,
    options: {
      plugins: [
        `gatsby-remark-prismjs`,
      ]
    }
  }
]
```

#### inline highlight


```java
public class HelloWorld {
    public static void main( String[] args ) {
        System.out.println( "Hello World!" );
        System.exit( 0 ); //success
    }
}
```

```javascript
var t = { a : 1 };
```

