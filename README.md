# keloran_fr

**EN**:

A theme for [JSONResume][jsonresume], that relies on [Bootstrap][bootstrap] and [FontAwesome][fontawesome], added with some personal flair.

This is a fork of [Keloran][keloran] that is a fork of [Kendall][kendall] with tweaks.

**FR**:

Un thème pour [JSONResume][jsonresume], qui s'appuie sur [Bootstrap][bootstrap] et [FontAwesome][fontawesome], modifié avec une certaine touche personnelle.

C'est un fork de [Keloran][keloran] qui est un fork de [Kendall][kendall] avec des modifications.

## Getting started

### Install the command line

Create your resume in json on [jsonresume](https://registry.jsonresume.org)

The official [resume-cli](https://github.com/jsonresume/resume-cli) to run the development server.

Go ahead and install it:

```
sudo npm install -g resume-cli
```

### Install and serve theme

This is a theme for JSON Resume. It is available via npm:

```
npm install jsonresume-theme-keloran-fr
```

then change directory:

```
cd node_modules/jsonresume-theme-keloran-fr/
```

And simply run:

```
resume serve
```

You should now see this message:

```
Preview: http://localhost:4000
Press ctrl-c to stop
```

Congratulations, you've made it!

## Tips

As of now, the theme supports the following profiles in the basics.profiles array.

* Facebook
* Github
* Twitter
* Google Plus
* YouTube
* Vimeo
* Linkedin
* Pinterest
* Flickr
* Behance
* Dribbble
* CodePen
* Soundcloud
* Steam
* Reddit
* Tumblr
* Stack Overflow
* Bitbucket
* Gitlab

Every single one of these is optional, and every field in the basics.profiles array **must** be entered without spaces. This theme will try to use the matching `-square` version of the icon from FontAwesome if it doesn't already have support for one of your profiles. If you want support for more social networks, feel free to leave an issue, or even better, submit a pull request. Thanks.

If you want to keep your resume mobile-friendly, please limit the number of profiles to 10, please. No one should have over 10 profiles on their resume anyway.

Every section is optional also. If per se, you do not include the publications array in your resume.json, no publications section will appear.

If you find any other problems with this theme in specified, do feel free to leave an issue. Thanks.

[jsonresume]:https://jsonresume.org/
[fontawesome]:http://fontawesome.io/
[keloran]:https://github.com/Keloran/jsonresume-theme-keloran
[kendall]:https://github.com/LinuxBozo/jsonresume-theme-kendall
[bootstrap]:http://getbootstrap.com/
