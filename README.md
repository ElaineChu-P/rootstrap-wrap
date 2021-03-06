# bootstrap-wrap

A wrapper for editing the Lessig2016 port of Twitter Bootstrap.

## Installation

1. Clone the repository.

    ```
    git clone https://github.com/Lessig2016/bootstrap-wrap.git
    ```

1. Install the dependencies.

    ```
    cd bootstrap-wrap
    npm i
    ```

1. Intall the Lessig2016/bootstrap submodule.

    ```
    git submodule init
    git submodule update
    ```

## Developing

1. Start the development environment.

    ```
    npm start
    ```

    This is a shortcut for running the `develop` Gulp task.

    ```
    npm run gulp develop
    ```

1. Each Gulp task can be run following the above pattern.

    ```
    npm run gulp taskname
    ```

    The following tasks are available:

    * `build-styles` - build Bootstrap core and theme CSS
    * `build-styles-core` - build Bootstrap core CSS
    * `build-styles-theme` - build Bootstrap theme CSS
    * `build` - build Bootstrap CSS, copy Bootstrap JS and fonts and site assets
    * `clean` - remove the build directory
    * `copy-assets` - copy the site assets
    * `copy-fonts` - copy Bootsrap fonts
    * `copy-scripts` - copy Bootstrap JS
    * `default` - alias for `develop`
    * `develop` - sequence for `build`, `serve`, `watch`
    * `serve` - run a static webserver
    * `watch` - set up filesystem watchers on Bootstrap .less files and public directory

1. Preview the site at [http://localhost:8440/](http://localhost:8440/). The port can be configured in the `tasks/constants` file.

## Code of Conduct

The Lessig Equal Citizens Exploratory Committee is committed to fostering an open and inclusive community where engaged, dedicated volunteers can build the strategy and tools necessary to fix our country's democracy. All members of the community are expected to behave with civility, speak honestly and treat one another respectfully.

This project adheres to the [Open Code of Conduct](http://todogroup.org/opencodeofconduct/#Lessig2016/conduct@lessigforpresident.com). 
By participating, you are expected to honor this code.

This reference as well as the included copy of the [Code of Conduct](https://github.com/Lessig2016/bootstrap-wrap/blob/master/CONDUCT.md)
shall be included in all forks and distributions of this repository.

## Legal

The Lessig campaign is not responsible for the content posted to this repository, or for actions taken or liabilities incurred by one or more group members. 

You may not post content to the repository that you do not own, and by posting content you consent to its use by others, including the campaign. 

You are responsible for your compliance with federal campaign finance laws. You may not, for example, volunteer for the campaign if you are being paid by someone else to do so, or volunteer while at work unless it is limited to a few hours per month and your volunteering doesn’t create additional costs for your employer.

The campaign may remove any offensive, abusive, attacking, or discriminatory content, as well as any content that may otherwise violate our [Terms of Service](https://lessig2016.us/terms-of-service/). 

## Copyright and License

Copyright 2015 Lessig Equal Citizens Exploratory Committee. This 
project is released under [GNU General Public License, version 3](https://github.com/Lessig2016/bootstrap-wrap/blob/master/LICENSE).

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

---

Portions of [Style Guide Boilerplate Bootstrap Edition](https://github.com/kemie/Style-Guide-Boilerplate-Bootstrap-Edition) were used to build the style guide. Style Guide Boilerplate Bootstrap Edition is licensed under the [MIT License](http://en.wikipedia.org/wiki/MIT_License).

