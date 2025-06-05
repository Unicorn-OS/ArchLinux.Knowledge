# if Makepkg asks for sudo, Heres How to Automate it.
sch:
- https://www.google.com/search?q=sudo+password+to+makepkg+in+script
- https://www.google.com/search?q=pass+password+to+sudo+in+script

...
- https://www.google.com/search?q=script+pass+sudo+to+makepkg
- https://www.google.com/search?q=makepkg+PACMAN_AUTH

# Solution:
https://bbs.archlinux.org/viewtopic.php?id=251411

```
sudo -u $username makepkg -s
```

##
[How to ask for root password from the user for my GUI app which pipes it to makepkg?](https://unix.stackexchange.com/questions/768977/how-to-ask-for-root-password-from-the-user-for-my-gui-app-which-pipes-it-to-make)
