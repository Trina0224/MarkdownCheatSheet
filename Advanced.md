# Table Example
This is above the table.

| Col Head 1 | Col Head 2 | Col Head 3|
|------------|------------|-----------|
| R1, C1     | R1, C2     | R1, C3    |
| R2, C1     | R2, C2     | R2, C3    |
| R3, C1     | R3, C2     | R3, C3    |

This is below the table. 

Don't worry about final reasults when you are typing in the table. The system will detect it's a table later. 

| Col Head 1 | Col Head 2 | Col Head 3|
|------------|:------------|-----------:|
| R1, C1     | R1, C2     | R1, C3    |
| R2, C1     | R2, C2     | R2, C3    |
| R3, C1     | R3, C2     | R3, C3    |

You could use `:` to line up left or right side. As above example.  

# Fenced Code Block
I already cover this in [Basic.md](https://github.com/Trina0224/MarkdownCheatSheet/blob/master/Basic.md#code-style-or-block "Trina's Basic.md") file 
We use three \``` to hold a block. Ex. Angular Componet
```
@Component({
selector:  'app-todo',
templateUrl:  './todo.component.html',
styleUrls: ['./todo.component.css']
})
```

The cool thing is you could high-light the code. Just let system know what kinds language of this code. Let's see this:
```JavaScript
@Component({
selector:  'app-todo',
templateUrl:  './todo.component.html',
styleUrls: ['./todo.component.css']
})
```
or
```HTML
<body  class="mat-typography">
	<app-root></app-root>
</body>
```

I put JavaScript and HTML after \``` 

