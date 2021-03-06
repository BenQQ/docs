---
title: Metropolis: Recreating the Demo - Copyright
description: Your Guide to Recreating Elements of the Metropolis Theme for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/metropolis:Metropolis

---

Copyright Section
-----

![][demo2]

:	1. **Gantry Copyright** [35%, 7%, se]
	2. **Custom Menu** [35%, 35%, se]
	3. **Gantry To Top** [35%, 86%, se]

Here is the widget breakdown for the Copyright section:

* Gantry Copyright
* Gantry Divider
* Custom Menu
* Gantry Divider
* Gantry To Top
* Gantry Social Buttons

The Copyright section remains the same for all areas of the site. Because of this, it is preserved as a Default widget override.

#### Gantry Copyright
The Gantry Copyright widget places a tiny Copyright notification at the bottom of the page. The only thing you need to change in this widget to match the demo is the text field, which includes: `Designed by RocketTheme`. 

#### Gantry Divider
This widget tells WordPress to start a new widget column beginning with the widget placed directly below the divider in the section.

#### Custom Menu
The Custom Menu widget allows us to add an extra menu at the bottom of the page. This menu was created separately from the main menu linked in the header, and can be configured by going to **Administration -> Appearance -> Menus**.

Here is a breakdown of what you will need to change in the widget options to match the demo.

* Set the **Select Menu** option to match the name of the menu you wish to appear in this area.
* Add `rt-dark-block horizmenu nomarginleft nomarginright nopaddingleft nopaddingright hidden-phone` to the **Custom Variations** field.
* Leaving all other options at their default settings, click **Save**.

#### Gantry To Top
The Gantry To Top widget is a simple indicator which allows users to jump to the top of a page with a single click. Just click and drag this widget into the section to activate it.

#### Gantry Social Buttons

![][social]

:	1. **Social Buttons** [10%, 8%, sw]

The Gantry Social Buttons widget creates a floating set of social buttons on the left side of the page. We placed it in the Copyright widget section so it is present in all of the demo pages. Filling this out is fairly straightforward as you will want to add your various social URLs to their respective fields before hitting **Save**.

[demo2]: assets/wp_metropolis_demo_2.jpeg
[social]: assets/social.jpg