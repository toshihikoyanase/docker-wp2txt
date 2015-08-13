# docker-wp2txt
wp2txt on docker

Extract plain text from wikipedia dump by using wp2txt
https://github.com/yohasebe/wp2txt

# Run

    $ mkdir /path/to/wikidump
    $ mkdir /path/to/wikidump/text
    $ docker run -it -v /path/to/wikidump:/mnt/wikidump toshihikoyanase/wp2txt /bin/bash
    # cd /mnt/wikidump
    # time wp2txt -i jawiki-20150805-pages-articles.xml.bz2 -o text/
