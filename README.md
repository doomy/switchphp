# switchphp
simple bash tool to switch php version used in apache &amp; console in ubuntu / debian based linux

## limitations 
currently works only with PHP 7.4 / PHP 8.0 versions. Savvy user should have no issues to change these to whichever versions one needs to alternate between. You still need to be aware which versions you have installed

## installation
copy it to wherever your executable folder `sudo cp switchphp /usr/bin/` and set executable rights `sudo chmod +x /usr/bin/switchphp`

## running
`phpswitch 8.0 // switches from 7.4 to 8.0`

