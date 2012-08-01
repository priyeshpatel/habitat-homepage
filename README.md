# habitat homepage

The habitat homepage powered by the habitat template.

by Priyesh Patel, 2012

## deploying:

Rather than check out the git repository in the web root, which may
be a pain if you plan on hosting anything else,

    $ cd /var/www/wherever/
    $ git clone git://github.com/ukhas/habitat-homepage.git homepage
    $ ln -s homepage/index.html .

index.html has a <base /> tag that makes it look for its images and css
inside /homepage/
