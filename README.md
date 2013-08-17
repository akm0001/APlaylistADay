APlaylistADay
=============

A web app and service that each day generates a new playlist with songs based on events that happened on this day in history/music.

#Flow
* Finds events that happened in a particular day in the history of music
* Finds an artist for each of the events
* Generates a song for each of the artists

#Requirements
 It requires the following perl packages that you can find on cpan:
* [Mojolicious](http://search.cpan.org/~sri/Mojolicious-4.24/lib/Mojolicious.pm)
* [YAML::XS](http://search.cpan.org/~ingy/YAML-LibYAML-0.41/lib/YAML/XS.pm)
* [Mojolicious::Plugin::YamlConfig](http://search.cpan.org/~data/Mojolicious-Plugin-YamlConfig-0.1.5/lib/Mojolicious/Plugin/YamlConfig.pm)

#Installation
 1. Install cpanminus. On a Debian-based Linux distribution you can do:
     `sudo apt-get install cpanminus`
 2. Install every perl module in the requirements section using cpanminus
    `sudo cpanm Mojolicious YAML::XS Mojolicious::Plugin::YamlConfig`
 3. Clone this project:
    `git clone https://github.com/Shemahmforash/APlaylistADay.git`
 4. Change to the directory of the application:
    `cd APlaylistADay`
 5. Run the application using:
    `morbo script/aplaylist_aday`
 6. Go to http://127.0.0.1:3000/ and see the program running
