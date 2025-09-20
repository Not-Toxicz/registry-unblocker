# Registry Unblocker
Any application that has administrator can make, change, or delete registry keys. Registry keys being the backbone of windows operating system. This being said malicious programs can and will use them to disable functions on your computer. I won't be giving the methods or names or the keys but I'll tell you how to fix it.

# Warning
If you don't know anything about registry keys, I wouldn't follow this tutorial. If you still choose to follow through, I have no resposiblity for what could happen to your computer. Also don't delete anything unless it was said in a step, don't brick your computer.

# Table of context
"->" open the drop down box for the given variable. \
Other stuff that's not explained in the tutorials will be added here. (Help the people with readability of the text)

### Before Every tutorial (set-up)
1. Open your registry editor. \
2. if your computer is set up right User-Account-Control will prompt you and allow the app to make changes. \
(This is a window application, it won't make changes unless you and/or an app (with privilege) gives it the instructions to)

### Disabled Task Manager by malicious software
3. Go to your HKEY_CURRENT_USER -> Software -> Microsoft -> Windows -> CurrentVersion -> Policies

4. From there click on System. (If you don't see System, then your problem stems further than registry keys) \
5. Inside "HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies\System" there shouldn't be any Keys. \
6. The only thing that should be in this directory is a SZ file with the name "(Default)". \
7. If you have any other key in that directory, and can't open Task Manager. Delete the key with the very obvious name. (You'll know which one)

### Disabled Control Panel by malicious software
3. Go to your HKEY_CURRENT_USER -> Software -> Microsoft -> Windows -> CurrentVersion -> Policies

4. From there click on Explorer. (If you don't see Explorer, then your problem stems further than registry keys) \
5. Inside "HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer" there shouldn't be any Keys. \
6. The only thing that should be in this directory is a SZ file with the name "(Default)". \
7. If you have any other key in that directory, and can't open Task Manager. Delete the key with the very obvious name. (You'll know which one)
