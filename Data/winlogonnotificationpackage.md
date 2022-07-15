## Winlogon Notification Package  <!-- general "title" of the persistence. Good to be unique. -->
<!-- separate sections by two empty lines -->
<!-- do not remove empty sections  -->


### Location: <!-- where to find it -->
`HKLM\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\Notify`


### Classification: <!-- see "how it works" document. Empty lime must go next. -->

|Criteria|Value|
|:---|:---|
|Permissions|Admin|
|Security context| System; User |
|Persistence type| Registry |
|Code type|DLL|
|Launch type|Automatic|
|Impact|Non-destructive|
|OS Version|All OS versions|
|Dependencies|OS only|
|Toolset|Scriptable|


### Description:<!-- add two EOLs or two spaces at the end of line to create a line break -->
Well documented. May be used to launch arbitrary code on different events, and in both - System, and user context.
> Winlogon notification packages are DLLs that receive and handle events generated by Winlogon. You can implement such a notification package to monitor and respond to Winlogon events.

### References: <!-- use <...> or [abc](https://...) syntax. Prepend with "- " when more than one -->
<https://docs.microsoft.com/en-us/windows/win32/secauthn/winlogon-notification-packages>


### Credits: <!-- use [abc](https://...) syntax. Prepend with "- " when more than one. -->


### See also: <!-- if refering to the same repo, use [Name](file.md) syntax. -->
<!-- prepend with "- " if more than one -->


### Remarks: <!-- see the usage in the "classification" section. Use only 1:1 references i.e. not refering to the same footnote from two different places -->
