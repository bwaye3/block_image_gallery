# *Add to the subtheme.libraries.yml*

#Image Gallery <br />
image-gallery: <br />
version: "1.0.x" <br />
css: <br />
theme: <br />
//cdnjs.cloudflare.com/ajax/libs/baguettebox.js/1.10.0/baguetteBox.min.css: { type: external } <br />
templates/block/custom/image_gallery/css/cards-gallery.css: {} <br />
dependencies: <br />
- core/jquery <br />

# *Add to the repositories section in the composer.json*

"repositories": [ <br />
{ <br />
"type": "vcs", <br />
"url": "https://github.gatech.edu/ICWebTeam/block_image_gallery.git" <br />
}
# *Add to the requirement in the composer.json*

"require": { <br />
"drupal/paragraphs": "^1.12",<br />
"gt/image_gallery": "dev-master", <br />
"mnsami/composer-custom-directory-installer": "^2.0"
},

# *Add to the installer paths in the composer.json*
"installer-paths": { <br />
"web/themes/contrib/subtheme/templates/block/custom/{$name}": [ <br />
"gt/image_gallery" <br />
] <br />
},

# *Install the Paragraphs Module*
https://www.drupal.org/project/paragraphs


# **CUSTOM BLOCK  SET-UP**
![](images/set-up.png)

