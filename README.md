# Cibo
Danbooru Ripper/Viewer cli tool

Things you will need to run this: Perl, wget, curl, Feh.

Use -t or --tags to specify tags. For multiple tags put a plus sign between the tags. If no tags are specified then the homepage will be used

Use -p to view pages. If one number is passed then only that page is used. If two pages are sent then those pages will be used and everthing between them. If no page is specified then the first page is used.

Use -v to view images on a page. Feh must be compiled with curl support.

Use -d to downlaod images with wget. Images will be saved to current directory.

TODO

* search funcitionality to seach through pools, tags, artists.
* config file
* Gelbooru and other booru support
* support for using an account
* setting a locaiton for saving images.
