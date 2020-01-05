# mkinitcpio-date
If you like to unlock a cryptdevice on a remote server which doesn't own a public ip you can use tinyssh, encryptssh and tor [1] in the initramfs.
However, in order to run a tor service in your early userspace you need the correct date and time. If your server doesn't have a RTC you can pull date and time from a well known IP with this little script.

[1] https://github.com/grazzolini/mkinitcpio-tor
