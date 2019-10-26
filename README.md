# :mag_right: iCMS - Content management system identifier
 
 With a simple python3 script, you can get the cms of any website!
# :clipboard: Features:
 - Multithread
 - List scan
 - Scan `Wordpress, Joomla, Drupal, Laravel, vBulletin, OpenCart, PrestaShop` CMS's
 - 2 Modes:
 
 `1. Normal Mode: basic website Scan`
 
 `2. Advance Mode: multipaths scan to get more than one CMS on website (example: site.com is a Wordpress CMS; site.com/forums is a vBulletin CMS, with advance mode you will get both)
 `
# :grey_question: Usage:
 - argument `-l` or `--list` and put name of your list of websites.
 - argument `-m` or `--mode` and choose your working mode, 1 for normal mode and 2 for advance mode.
 - argument `-t` or `--thread` and select your number of threads you want to work with.
 
Example: `python iCMS.py -l sites.txt -m 1 -t 100`

# :electric_plug: Requirements:
1. python 3
    - install python version 3.x on your OS.
2. requests lib
    - install requests lib using pip, you can use this command line `pip install requests`
