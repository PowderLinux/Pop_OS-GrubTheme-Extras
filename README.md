# Pop_OS-GrubTheme-Extras
Extra fonts/theme.txt for Pop_OS-GrubTheme
______________________________________________________________

Extra fonts with their matching theme.txt's to use with Pop_OS-GrubTheme
(https://github.com/PowderLinux/Pop_OS-GrubTheme)

______________________________________________________________

These are fonts that I tried using when I originally created my Pop_OS-GrubTheme.
(the fonts that System76 uses on Pop_OS). I ended up not including them in the theme tho
because I didnt like the way they came out after converting them to grub's .pf2 format.
However, I figured that I would upload them anyway for anyone that would like to try them.
(I think the Fira Mono Bold ended up looking the best out of the bunch).
I made this easier for anyone that wants to tese these by adding theme.txt's for each font.

______________________________________________________________

How to use these new fonts in your grub theme:


Copy the fonts that you want to try into the Pop_OS-GrubTheme folder >
(you need to copy both sizes. ex: for Fira Sans, copy firasans_14.pf2 & firasans_16.pf2)

Delete the theme.txt that is in the Pop_OS-GrubTheme folder >

Copy the new '(Font Name) theme.txt' for the font you want to try in the Pop_OS-GrubTheme folder >

Rename '(Font Name) theme.txt' to 'theme.txt' >

Run 'sudo update-grub'

Done. (Repeat for every font you want to try)

______________________________________________________________

Created by p0wder (https://github.com/PowderLinux)


Credits:

Andrei Shevchuk (https://github.com/shvchk)
I used his 'Poly-Light' grub theme as a template to make the theme.txt's in this repo.
(copy of MIT License is included)

______________________________________________________________
