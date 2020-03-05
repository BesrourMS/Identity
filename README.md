# Identity
HTML5UP Identity Template For Pico CMS

Download the identity folder, extract it to the themes folder of your Pico installation, and change the following setting within your config.php for Pico CMS Version < 2.0 :

`$config['theme'] = 'identity';`

For Pico CMS >= 2.0 add to config/config.yml

`theme: identity`

(If the file does not excist, create it. For more info see config/config.yml.template)

For the content download our `index.md`, upload it in the content folder and make your changes.

You can add as many social icons as you want using the follow syntax:

```
Social:
  http://tn.linkedin.com/in/MohamedSafouanBesrour: linkedin
  https://github.com/BesrourMS: github
  url: icon
```

(Make sure to use spaces for indentation and not tabs!)

For the Social Icons we use [Font Awesome](https://fortawesome.github.io/Font-Awesome/).  You can find a list of all available icons [here](https://fortawesome.github.io/Font-Awesome/icons/).

For your Avatar Image, you can add an image to your site and specify its path using the meta Image variable in the index.md:
`Image: assets/avatar.jpg`

([Pico recommends](http://picocms.org/docs/#creating-content) placing images inside an "assets" folder!)

For the Background replace the `bg.jpg` in Identity's `images` folder with your own background image.

Recommended Sizes:

`avatar.jpg => 122x122 px | bg.jpg 1440x900 px`

#### Demo: http://html5up.net/uploads/demos/identity/
