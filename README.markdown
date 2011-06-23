# TextMate bundle for Faker gem

## Instalation

### create directory ~/Library?Application\ Support/TextMate/Bundles if not exist yet

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles

### go to your TextMate bundles directory

    cd ~/Library/Application\ Support/TextMate/Bundles

### with Git:

    git clone http://github.com/tinogomes/faker-tmbundle.git Faker.tmbundle
    osascript -e 'tell app "TextMate" to reload bundles'

### without Git:

    wget http://github.com/tinogomes/faker-tmbundle/tarball/master
    tar zxf tinogomes-faker-tmbundle-*.tar.gz
    rm tinogomes-faker-tmbundle-*.tar.gz
    mv tinogomes-faker-tmbundle-* Faker.tmbundle
    osascript -e 'tell app "TextMate" to reload bundles'

## Contributors

* [Tino Gomes][1]

## License

Copyright (c) 2011 Tino Gomes, released under the MIT license

[1]: http://github.com/tinogomes "Tino Gomes"