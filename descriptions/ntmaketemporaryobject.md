This function is [documented in Windows Driver Kit](https://learn.microsoft.com/en-us/windows-hardware/drivers/ddi/wdm/nf-wdm-zwmaketemporaryobject)

\(Also avaiable in Win2000 DDK\) \
Function clears object's PERMANENT flag, so it's live as \
long as the latest HANDLE is closed. \
ObjectHandle HANDLE to object to \
make temporary.

Documented by: \
Tomasz Nowak \
Requirements:

Library: ntdll.lib

See also: \
NtClose \
NtQueryObject