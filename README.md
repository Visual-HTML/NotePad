# NotePad
Hold elements for 20170616 designer. https://visual-html.github.io/V-HTML/Bootstrap001.html

Designer code bring a search on this repository, search for table, target the place and click select.
expected result: table code is added (nothing appear... click clear then edit)

It's a repository used as source for component codes

A designer code can query this repository looking for components (here a table html code)

Next: Ensure the injected code appear as editable element ; load its 'controller' : a code that can manage the code of the table this code must also be variable ; using standards different codes could run on elements injected by other because the structure is known.  Difficulty, before changing a value is to evaluate if it will not make invisible (reset url of a form?) or visible 'errors' or unexpected behaviors (width 100% set to element with screen.width = change % and to px ?...).  There are simple changes ?.. not really 

   - the title attribute is simple its defined one way, its always on the element
   - the background color of an element is complex: it is on the element or within a style (and the current one) - any attribute set with css/style attribute string + dom style element?
   - more complex and huge chance to fail: sizing, positioning, canmake the complete layout invalid
   - ssssssssssssssssssssssssssssssssssssssssssssssssssssssssssssssssssssssssssssssssssssssssssssssss
    
   loading/reloading the component that generated the code can help
    or a code that first explore in detail the values on which it will act and choose a way to act
    ==> with expressed in %,load a designer code that change the width using % values
    the same for a code that query using XMLHttpRequest, the need is first a query level but it can also be at processing received data, it is programming too.
    

(designer, components).  If it does a lot, of specific it mustbe defined as exclusive controller and 'extension',encapsulation, compositions on that code must be used, and it introduce a code dependency) 
