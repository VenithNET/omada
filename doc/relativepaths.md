# Documentation
## Please, never use ../ or any relative file paths ever again. I beg of you.


`../` - Do not use, this will result in general breakge and headaches. <br>
`index.html` - Unneeded, bloat, those 2 bytes are too much. Bad. do "/" instead.

Good:
```
<p><a href="/">Go back home</a></p>
<img href=/assets/omada-home.png alt="logo">
```

Bad:
```
<p><a href="../../../../index.html>Go back home</a></p>
<p><a href="/index.html>Go back home</a></p>
<img href=../../../../assets/omada-home.png alt="logo">
```

