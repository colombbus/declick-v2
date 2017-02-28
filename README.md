# Declick v2

Declick is an educational and creative platform to learn how to build apps and to create and publish apps, collaboratively with other users.

[www.declick.net](http://www.declick.net)

## Components

Declick v2 is split into three components, each of which has its own repository:
* [declick-server](https://github.com/colombbus/declick-server-v2), a server written on PHP built on [Lumen platform](https://lumen.laravel.com)
* [declick-ui](https://github.com/colombbus/declick-ui), a user interface written in JS built on [Vue.js](https://vuejs.org)
* [declick-client](https://github.com/colombbus/declick-client-v2), a client written in JS, that includes creation and exercisz interfaces, as well as the runtime used by the apps. Ultimately, declick-client will be split into two parts:
    * creation and exercise user interfaces will be included into declick-ui
    * runtime will lead to a new component, declick-runtime

## Installation

You may download every component separately or download all components at once, using the following command:
```
git clone --recursive https://github.com/colombbus/declick-v2.git
```
For installation and configuration, see instructions relative to each part, in corresponding repositories.

## License

Declick v2 platform is open-sourced software licensed under the [GPLv3 license](https://opensource.org/licenses/GPL-3.0)