Taking the course of *Github Pages with Jekyll*

# Markdown

[Markdown Cheatsheet](https://guides.github.com/features/mastering-markdown/)

## Links

URL as plain text is automatically turned to a link, like this one:
https://guides.github.com/

The titled link,
[Markdown Cheatsheet](https://guides.github.com/features/mastering-markdown/)
, is produced by

    [Markdown Cheatsheet](https://guides.github.com/features/mastering-markdown/)


## Code

    ```javascript
    function fancyAlert(arg) {
      if(arg) {
        $.facebox({div:'#foo'})
      }
    }
    ```
produces

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

You can also simply indent your code by four spaces:

    function fancyAlert(arg) {
      if(arg) {
        $.facebox({div:'#foo'})
      }
    }

