About plugins
-------------

Hydrogen now support extensions of type
`org.freedesktop.LinuxAudio.Plugins`. Currently they depend on
freedesktop 22.08 (which the KDE 5.15-22.08 runtime depend on).

So careful consideration should be to update the runtime as this will
remove the extensions that the user might have installed and expect.

metadata license
----------------

Sadly the appstream file checks must be skipped due to improper
metadata license, which an issue has been fixed upstream for.

source
------

Use git source otherwise the build will be marked as development.
