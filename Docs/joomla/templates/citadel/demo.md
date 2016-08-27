---
title: Citadel: Recreating the Demo
description: Your Guide to Recreating Elements of the Citadel Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/citadel:Citadel

---

Introduction
-----

Recreating features of the demo site used to show off some of the more interesting aspects of Citadel can be done fairly easily. All you need is the right extensions and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Citadel Template.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the Joomla back end. We have added most of these elements into the template's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Module and Particle Settings
-----

Below, you will find the module placement and settings for the various module positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

![](assets/citadel2.jpeg)

:   1. **Navigation Main** Logo (Particle) [1%, 15%, se]
    2. **Navigation Main** Menu (Particle) [1%, 30%, se]
    3. **Slideshow Main** Simple Content (Particle) [6%, 17%, se]
    4. **Slideshow Main** Video (Particle) [4%, 10%, se]
    5. **Header Main** Simple Content (Particle) [15%, 10%, se]
    6. **Header Main** Info List (Particle) [20%, 10% se]
    8. **Above Main** Owl Carousel (Particle) [28%, 10%, se]
    8. **Above Main** Owl Carousel (Particle) [28%, 68%, se]
    9. **Showcase Main** Simple Content (Particle) [43%, 15%, se]
    10. **Showcase Main** Video (Particle) [39%, 15%, se]
    11. **Showcase Main** Custom HTML (Particle) [37%, 35%, se]
    12. **Feature Main** Owl Carousel (Particle) [52%, 13%, se]
    13. **Feature Main** Block Content (Particle) [52%, 50%, se]
    14. **Expanded Main** Info List (Particle) [65%, 13%, se]
    15. **Extension Main** Info List (Particle) [75%, 13%, se]
    16. **Footer Main** Custom HTML (Particle) [83%, 12%, se]
    17. **Footer Main** Simple Form (Particle) [83%, 50%, se]
    18. **Copyright Main** Logo / Image (Particle) [97%, 48%, se]
    18. **Copyright Main** Bottom Menu (Particle) [98%, 35%, se]
    19. **Copyright Main** Copyright (Particle) [99%, 40%, se]

Not pictured here is an **Offcanvas** position which hosts the mobile menu. You can find out more about the Offcanvas position in the [Gantry 5 documentation](http://docs.gantry.org/gantry5/configure/layout-manager#offcanvas-section).

Particles
-----

Here is a list of particles that are available in Citadel, as well as links to documentation to help you get started:

* Template Particles
    * [Owl Carousel](particle_owl.md)
    * [Video](particle_video.md)
    * [Pricing Table](particle_pricing.md)
    * [Joomla Articles](particle_joomla.md)
    * [Block Content](particle_block.md)
    * [Info List](particle_info.md)
    * [Grid Statistic](particle_grid.md)
    * [Simple Content](particle_simple.md)
    * [Image Grid](particle_image.md)
* Core Particles 
    * [Logo](http://docs.gantry.org/gantry5/particles/logo)
    * [Menu](http://docs.gantry.org/gantry5/particles/menu-control)
    * [To Top](http://docs.gantry.org/gantry5/particles/to-top)
    * [Social](http://docs.gantry.org/gantry5/particles/social)
    * [Module Positions](http://docs.gantry.org/gantry5/particles/position)
    * [Spacer](http://docs.gantry.org/gantry5/particles/spacer)
    * [Mobile Menu](http://docs.gantry.org/gantry5/particles/mobile-menu)
    * [Custom HTML](http://docs.gantry.org/gantry5/particles/custom-html)
    * [Module Instance](http://docs.gantry.org/gantry5/particles/module-instance)
    * [Page Content](http://docs.gantry.org/gantry5/particles/page-content)
    * [System Messages](http://docs.gantry.org/gantry5/particles/system-messages)

Core Gantry Particles (Documented on [Gantry's Website](http://gantry.org)):

* [Logo](http://docs.gantry.org/gantry5/particles/logo)
* [Menu](http://docs.gantry.org/gantry5/particles/menu-control)
* [To Top](http://docs.gantry.org/gantry5/particles/to-top)
* [Social](http://docs.gantry.org/gantry5/particles/social)
* [Module Positions](http://docs.gantry.org/gantry5/particles/position)
* [Spacer](http://docs.gantry.org/gantry5/particles/spacer)
* [Mobile Menu](http://docs.gantry.org/gantry5/particles/mobile-menu)
* [Custom HTML](http://docs.gantry.org/gantry5/particles/custom-html)
* [Module Instance](http://docs.gantry.org/gantry5/particles/module-instance)
* [Page Content](http://docs.gantry.org/gantry5/particles/page-content)
* [System Messages](http://docs.gantry.org/gantry5/particles/system-messages)

Recommended Extensions
-----

Here is a list of RocketTheme extensions used to create the demo version of Citadel:

* [Gantry 5 Theme Framework](http://gantry.org/)
* [RokBox](http://www.rockettheme.com/joomla/extensions/rokbox)
* [RokBooster](http://www.rockettheme.com/joomla/extensions/rokbooster)

Many of these extensions are included with the Citadel RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Citadel demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the template. It is because of this that several module and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Citadel demo.

Home Page Layout Presets
-----

![Layout Presets](assets/layout_presets.jpeg)

In order to make it really easy to replicate the home page, we included two layout presets for the home page with the theme. The first, **Home - Particles** (included in the standalone package) includes all of the particle-based home page demo content so you can hit the ground running with a copy of our demo to work from loaded directly into the layout. If you downloaded the theme and not a RocketLauncher, this is the best option for you if you want a copy of the front page with minimal effort.

The other preset is called **Home - Positions** and this is used in our demo by default in the RocketLauncher. This option creates module positions which give you a little more flexibility to swap out demo particles with standard Joomla modules. Keep in mind that this Layout Preset will not fill in the **Gantry 5 Particle** modules, only the module positions we used in the layout for the demo. We've included this documentation to help you recreate specific elements if you opt to go with this layout preset on an existing site.

You can access the presets by selecting **Load** in the **Layout Manager**.

Menu Editor
-----

![](assets/menu_1.jpeg)

Citadel has its own built-in Menu Editor which takes full advantage of Joomla's menu system, taking your Joomla menus and enhancing them before passing them to visitors on the front end. Any changes made in the Menu Editor will only affect the way it appears to the visitor, and not the way Joomla sees or uses it.

You can access the Gantry Menu Editor by navigating to **Administrator > Components > Gantry 5 Themes > Citadel > Menu**. You can find out more about navigating and using the Gantry Menu Editor [in our documentation](http://docs.gantry.org/gantry5/configure/menu-editor).

Assignments
-----

![](assets/assignments_1.jpeg)

Assignments are also managed in the Gantry Administrator. This administrative panel enables you to assign theme outlines to specific menu items, pages, and other areas of your site. By navigating to **Administrator > Components > Gantry 5 Themes > Citadel** and selecting an outline other than the **Base Outline**, you will be able to assign that outline by navigating to the **Assignments** panel. Simply switch any menu items to on (green) that you want to assign that outline to. In the case of the Home page, this would be your default Home page in your default (main) menu.