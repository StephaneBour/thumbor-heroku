# Deploy thumbor on Heroku in one click


[![Deploy on Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/StephaneBour/thumbor-heroku)


Deploy [Thumbor](https://github.com/thumbor/thumbor) in one click.

## Configuration

In your Heroku Apps Settings, you can add, delete and edit config vars.

All vars in [thumbor.conf](thumbor.conf) can be edit.

By default, unsafe URL isn't enable, and the security key is `1234567890`

## Example

**Original :**

URL : `https://media.ouest-france.fr/v1/pictures/1b1c64cc260073d7cf4a9547bf9b672d-miss-france-2019-decouvrez-les-30-concurrentes-en-lice-pour-succeder-maeva-coucke.jpg`

![](https://media.ouest-france.fr/v1/pictures/1b1c64cc260073d7cf4a9547bf9b672d-miss-france-2019-decouvrez-les-30-concurrentes-en-lice-pour-succeder-maeva-coucke.jpg)

**Cropped :**

URL : `https://thumb-stephane.herokuapp.com/TOGRX42EFwp-26aNMwO11Ed2YWQ=/420x140/smart/filters:fill(green)/https://media.ouest-france.fr/v1/pictures/1b1c64cc260073d7cf4a9547bf9b672d-miss-france-2019-decouvrez-les-30-concurrentes-en-lice-pour-succeder-maeva-coucke.jpg`

![](https://thumb-stephane.herokuapp.com/TOGRX42EFwp-26aNMwO11Ed2YWQ=/420x140/smart/filters:fill(green)/https://media.ouest-france.fr/v1/pictures/1b1c64cc260073d7cf4a9547bf9b672d-miss-france-2019-decouvrez-les-30-concurrentes-en-lice-pour-succeder-maeva-coucke.jpg)
