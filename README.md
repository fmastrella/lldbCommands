# lldbCommands by Fausto Mastrella

Put .lldbinit file into your home directory.

You can put your .lldbinit in other places, but then Xcode won't automatically load it. If you put it somewhere other than ~/.lldbinit, you need to source it in Xcode in the LLDB session like this:

> (lldb) command source &lt;mypath&gt;/.llbinit 

where &lt;mypath&gt; is replaced by the path of your .lldbinit
