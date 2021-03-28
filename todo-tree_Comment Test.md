# Tags and formatting
For specific grouping, see settings.json

// ALERT
// CAUTION
// WARNING
// WARN
// BUG
// DEBUG
// DONE
// FIX
// FIXME
// FIXIT
// HACK
// NOTE
// TEST
// TESTING
// testisen3
// TODO
// QUESTION
// ?
// [ ]
// [x]


# Language Support

## Java
    // DONE : Java Comment

    // TODO : Java Block Comment
    //  All lines following triggerring line with $TAG must be preceeded by two spaces [ ]{2} or one tab \t.
    //  Third line

    /* 
        DONE Java
        MultiLine Comment
    */


## BATCH
    REM DONE : BATCH Comment

    : ' 
        DONE : BATCH
        Multiline Comment
    '

## Powershell/Python
    # DONE : Powershell/Python Block Comment

    # TODO : Powershell/Python
    #  All lines following triggerring line with $TAG must be preceeded by two spaces [ ]{2} or one tab \t.
    #  Third line 

    <# 
        DONE : Powershell 
        MultiLine Comment
    #>


## XML 
    <!-- DONE : XML/HTML comment -->

    <!-- 
        DONE : XML/HTML
        MultiLine Comment
    -->


# Comments (Not updated)

Source and ReadMe: https://github.com/Gruntfuggly/todo-tree 

Notera att kommentarerna visas här i editorn, varningar visas i marginalen. Nästan alla visas i overviewn till höger i scrollisten 
och samtliga dyker upp i trädet (egen knapp för att öppna trädet aldra längst till höger)

Alla keywords som den stödjer har du ovan, du kan även (typ) se grupperingen av dem där. (Fix, Hack och Todo är däremot 3 sepparata grupperingar som ser likadana ut)
För att se alla tags och faktisk indelning kan du kolla under "todo-tree.general.tags" och "todo-tree.general.tagGroups"

Skit som inte riktigt funkar som det ska, men som jag inte orkar fixa nu:
- Regex för substräng
- Block comments are currently not supported
- knappar för att hantera trädet (refresh, filter osv) syns inte.

Gör du nå ändringar får du gärna säga till, jag kanske blir inspirerad.