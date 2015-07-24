# PlayerBundle

PlayerBundle is an extension for **BackBee CMS** that integrate the most popular
web players.

## Installation

You need to install it with composer. In your BackBee project, execute this command:

```bash
$~ composer require "lp-digital/player-bundle"
```

And then you need to activate the bundle. In ``repository/Config/bundles.yml``
add this line:

```yaml
player: LpDigital\Bundle\PlayerBundle\Player 
```

## Players

Here a list of availables players:

* Dailymotion
* Youtube
* Vimeo
* Spotify
