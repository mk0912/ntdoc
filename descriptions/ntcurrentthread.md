This macro is a native equivalent of the [`GetCurrentThread`](https://learn.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-getcurrentthread) function. It returns a pseudo-handle that grants `THREAD_ALL_ACCESS` to the current thread. You do not need to call `NtClose` on the returned handle.

# See also
 - `NtCurrentProcess`
 - `RtlIsCurrentThread`