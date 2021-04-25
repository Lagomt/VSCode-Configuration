# Todo Tree (gruntfuggly.todo-tree) Comment Preview

Open file in VSCode to see highlighting

## Tags and formatting

For specific grouping, see settings.json

```Java
// ALERT
// CAUTION
// BUG
// DEBUG
// DONE
// FIX
// FIXME
// FIXIT
// HACK
// NOTE
// INFO
// TEST
// TESTING
// testisen3
// TODO
// WARNING
// WARN
// QUESTION
// ?
// [ ]
// [x]
```

## Triggers

Todo Tree is triggered by comment character, i.e. double slash "//" for java. Followed by a $TAG in $TAGS i.e. "TODO". Followed by either a space, newline/carriage return or colon.

### Valid Trigger Syntax

First line using newline [\n\r]
Second line using space \s
Third line using colon

```Java
// TODO
// TODO 
// TODO:
```

Below is the preffered method for readablility (subjectivly).

```Java
// TODO : Single Line Comment

// TODO
//  Block Comment without title.

// TODO : Title
//  Block Comment

/*
    TODO
    Multiline Comment without title.
*/

/*
    TODO : Title
    Multiline Comment
*/
```

## Language Support

### Java

```Java
    // DONE : Java Comment

    // DONE : Java Block Comment
    //  All lines following triggerring line with $TAG must be preceeded by two spaces [ ]{2}.
    //  Third line

    /* 
        DONE Java
        MultiLine Comment
    */
```

### BATCH

```Batch
    REM DONE : BATCH Comment

    : ' 
        DONE : BATCH
        Multiline Comment
    '
```

### Powershell/Python

```Powershell
    # DONE : Powershell/Python Block Comment

    # DONE : Powershell/Python
    #  All lines following triggerring line with $TAG must be preceeded by two spaces [ ]{2}.
    #  Third line 

    <# 
        DONE : Powershell 
        MultiLine Comment
    #>
```

### XML/HTML

```XML
    <!-- DONE : XML/HTML comment -->

    <!-- 
        DONE : XML/HTML
        MultiLine Comment
    -->
```

### CSS

``` CSS
    /* DONE : CSS */

    /*
        DONE : CSS
        Multiline Comment
    */
```

## Notes

Source and ReadMe: [Gruntfuggly.todo-tree](https://github.com/Gruntfuggly/todo-tree)
