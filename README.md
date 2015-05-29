# exeter-clojurians.github.io
Source for a site to stick info about what the Exeter Clojurian folk get up to.

# Structure

The site uses [Cryogen](http://cryogenweb.org/) to generate it's pages.

The Cryogen files are stored in /cryogen. To run the generator and watch for changes :

    > cd cryogen
    > lein ring server

Posts use Markdown and are in `/cryogen/resources/templates/md/posts`. Pages are in `/cryogen/resources/templates/md/pages`.

Template files are in `/cryogen/resources/templates/html/layouts`.

To publish the site you have to manually copy the files in `/cryogen/resources/public` to `/` cos that where github needs them. Then push to Github.
