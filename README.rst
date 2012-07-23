Introduction
============

Plone theme based on Twitter Bootstrap 2.0

Installation
============

Install the ``diazotheme.bootstrap`` product using the Add-on Control Panel.
This will activate the theme and also setup Plone's default ``public.css``
to only included when Diazo is enabled or when you are viewing the Theming 
Control Panel. This theme includes its own ``public.css`` which had several 
items from the default ``public.css`` removed.

Features
=========

* Turn your site into a pretty Bootstrap based theme, and also simplifies
  templating of customization addons.
* Portlets are converted to ``div`` elements instead of ``dl``, ``dt``, ``dd``
* ``Products.ContentWellPortlets`` is supported, however with some modifications. 

  * PortletAboveContentA will appear full width right below logo
  * PortletAboveContentB will appear full width right below breadcrumbs
  * PortletAboveContentC will appear fluid width right above content center 
    column
  * PortletBelowContentA, PortletBelowContentB, PortletBelowContentC will 
    appear as a 3 column portlet slots right below content and sidebar area
  * PortletBelowContentD will appear full width right below
    PortletBelowContentA, PortletBelowContentB, and PortletBelowContentC
  * All PortletFooter will appear as a 6 column slot within the footer area

* ``eea.facetednavigation`` is also supported, with some enhancements.

  * The diazo rules rewrite facetednavigation templates to take advantage of
    the responsive design.
  * If the first widget at the top widget slot is a text search widget, it will 
    appear as a full width widget with a different background.

* Installing ``webcouturier.dropdownmenu`` will enhance the top navigation with
  dropdown menus.
