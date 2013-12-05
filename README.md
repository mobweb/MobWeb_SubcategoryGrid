# MobWeb_SubcategoryGrid extension for Magento

This extension creates a template that can be inserted on any category page as a static block. It will then display this category's direct child categories. The markup is copied mostly from the default product grid, so most styles should be inherited from the product grid styles.

## Installation

Download & install using [colinmollenhour/modman](https://github.com/colinmollenhour/modman/). Or directly via git, using [jreinke/modgit](https://github.com/jreinke/modgit).

## Configuration

Create a new static block with the following content (make sure to disable the WYSIWYG editor when pasting the code):

``{{block type="mobweb_subcategorygrid/navigation" template="mobweb_subcategorygrid/catalog/navigation/subcategory_grid.phtml"}}``

Now go to your category's detail page and switch to the `Display Settings` tab. Set the `Display Mode` to `Static Block Only` and under `CMS Block` select the static block that you've just created.

## Questions? Need help?

Most of my repositories posted here are projects created for customization requests for clients, so they probably aren't very well documented and the code isn't always 100% flexible. If you have a question or are confused about how something is supposed to work, feel free to get in touch and I'll try and help: [info@mobweb.ch](mailto:info@mobweb.ch).