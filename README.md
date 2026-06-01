ETWSilence removes kernel level logging from windows, rather than disabling from usermode, we directly invalidate certain windows api calls, hooks etc.

MouseFix ensures that no matter what, the OS plays a minor part in 'feel and direct access to the mouse'. Mouse acceleration is disabled through the kernel rather than OS which is hindered by cpu cycles, timers, and overall throughput issues.
