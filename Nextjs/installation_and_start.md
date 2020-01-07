## Start the Development Server

### if npm
```npm run dev```

### if yarn
```yarn dev```

## Create a nextjs project with material UI
[ Material UI ](https://github.com/mui-org/material-ui/tree/master/examples/nextjs) <- Instructions are written in this repo.




## Styles
### Using Inline -> CssInJs
Example:   ```<p style={{color:"blue"}}>text</p>```
  
### Style jsx tag
##### block scope
Example: ```
          <style jsx>
  h1, a {
    font-family: "Arial";
  }
  a {
    text-decoration: none;
    color: blue;
  }

  a:hover {
    opacity: 0.6;
  }
</style>

         ```

##### global scope
Example:  ```
             <style jsx global>{`
        .markdown {
          font-family: 'Arial';
        }

        .markdown a {
          text-decoration: none;
          color: blue;
        }

        .markdown a:hover {
          opacity: 0.6;
        }

        .markdown h3 {
          margin: 0;
          padding: 0;
          text-transform: uppercase;
        }
      `}</style>
          ```
 
