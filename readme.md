# Set Up Sass with Prepros

- Download Prepros https://prepros.io/downloads

- Set Up Project 

Create in VS Code: 

- Index.html 
- styles.scss

Open up Prepros 

- Drag Project folder to Prepros

- Click on styles.scss in prepros with process automatically ticked

- Click Process File
Notification saying successful should pop up. 

- In VS code a new file should appear called styles.css

- Link css file in html file

```
    <link rel="stylesheet" href="styles.css" />
```

- Add practice code to scss file 

```
.rule{
    Color:red;
    a{
    Color:blue;
    Span{
        Color:pink;
    }
}
} 
```

This could appear in css file as css


 ```
.rule {
  Color: red;
}
.rule a {
  Color: blue;
}
.rule a Span {
  Color: pink;
}
```
You are now ready to begin! 