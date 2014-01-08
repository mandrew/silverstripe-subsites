# Subsites

The SilverStripe subsites module allows you to manage multiple related sites through a single CMS interface. Because all sites run on a single installation of SilverStripe, they can share users, content and assets. 
They can all use the same templates, or each use different ones.

A useful way to think of its use is where you have a business with a global headquarters and four branches in various countries. The subsites module allows the five offices to use a single SilverStripe installation, and have information from the headquarters flow down into the branches. The branches can have separate users/admins, and information that is individual. The website templates can also be different.

Features:
 * Each subsite appears as a standalone website from a users prospective
 * No need to duplicate existing code as all subsites use the same codebase as the main site
 * You can set permissions on each subsite domain name
 * Ability to copy a page and its content from the main site into a subsite
 * Create translations of subsite pages
 * Schedule the publishing of subsite pages

Limitations:
 * Each subsite domain name has to be set up on the server first
 * A subsite cannot use a different codebase as the main site, they are intrinsically tied
   * However, you can remove page types from a subsite when creating the subsite - [see the setup documentation for further details](set_up.md)
 * The only code a developer can edit between subsites is the theme

This document assumes that you have full admin rights for your site.

 1. [Setting up subsites](set_up.md)
 2. [Working with subsites](working_with.md)