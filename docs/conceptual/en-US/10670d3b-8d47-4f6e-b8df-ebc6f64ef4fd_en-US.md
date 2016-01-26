# Event.add<'T,'Del> Function (F#)

Runs the given function each time the given event is triggered.

**Namespace/Module Path:** Microsoft.FSharp.Control.Event

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## CAPS_SYNTAX_MD

```
// Signature:
Event.add : ('T -> unit) -> IEvent<'Del,'T> -> unit (requires delegate)

// Usage:
Event.add callback sourceEvent
```

#### CAPS_PARAMETERS_MD
*callback*
Type: **'T -&gt;**[unit](http://msdn.microsoft.com/en-us/library/00b837c2-6c8a-483a-87d3-0479c64037a7)


The function to call when the event is triggered.


*sourceEvent*
Type: [IEvent](http://msdn.microsoft.com/en-us/library/8dbca0df-f8a1-40bd-8d50-aa26f6a8b862)**&lt;'Del,'T&gt;**


The input event.




## CAPS_REMARKS_MD
This function is named **Add** in compiled assemblies. If you are accessing the function from a language other than F#, or through reflection, use this name.

**The following code example shows how to use the Event.add function.**
**[!CODE [FsEvents#1](../CodeSnippet/VS_Snippets_Fsharp/fsevents/FSharp/fs/program.fs#1)]**
## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Control.Event Module &#40;F&#35;&#41;](Control.Event+Module+%28F%23%29.md)

[Microsoft.FSharp.Control Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Control+Namespace+%28F%23%29.md)
