.. ==================================================
.. FOR YOUR INFORMATION
.. --------------------------------------------------
.. -*- coding: utf-8 -*- with BOM.

.. include:: ../Includes.txt


.. _a-short-glimpse-into-the-extension-manager:

A short glimpse into the extension manager
------------------------------------------

TYPO3 has many built-in features, but even more different ones are
implemented as extensions. With such an extension you can enhance the
functionalities of TYPO3 or build totally new features. Even a lot of core
features are implemented as extensions (plugins), so it is your choice
if you want to use that feature or not. The extension manager helps
you to manage all your extensions. Let's have a short glimpse
at the extension manager. First, log in as an admin and then switch to the extension
manager module.

.. figure:: ../Images/manual_html_m2bdcce4f.png
   :alt:

At the top of the module, you can either manage your existing extensions or search
and install new extensions from the TYPO3 Extension Repository, which is also called TER (#1).

Before downloading a new extension from the TER, make sure to press the "Update now"-Button (#2).
Otherwise you might get outdated results or none at all.

Now have a look at the list of loaded extensions.

.. figure:: ../Images/manual_html_4cb008fc.png
   :alt:


If there are updates for a given extension, you will see an update icon (#1) in the first column. 

The extension's current status (activated / deactivated) is shown by the icon's color in the second column (#2).
In order to activate or deactivate an extension, click on the icon. You might notice that
not all extensions have such an icon. This is due to them being important system extensions which are required by TYPO3.

The fourth column shows the extension key. It is a unique identifier and is, for example, used as the extension's folder name.

You can uninstall or install by
clicking on the icon (#1). The title (#2) of the extension is shown.
But more important is the extension key (#3). That key is used to
create the extension folder in typo3conf/ext/, to define TypoScript
paths and a lot more of depends on the extension key. The version (#4)
and the state (#8) is set by the extension developer based on his
judgement. You can download the extension itself (#5) or the manual
(#6) if one is shipped with that extension. The extension type (#7)
"System" indicates that an extension is shipped with the TYPO3 core,
extensions of type "Local" are available in typo3conf/ext/
*extensionkey* .

Some extensions are marked as "shy", so the list should not get to
long with unimportant extensions. Just check "Display shy extensions"
and have a look at the list.

.. figure:: ../Images/manual_html_m6d63c44d.png
   :alt:

Now let us install an new extension. For that switch to the sub-module
"Install extensions".

.. figure:: ../Images/manual_html_m3022c16c.png
   :alt:

Click on the "Retrieve/Update" Button to retrieve the latest list of
available extensions from the TER. Now let's look up for the extension
ts45min.

.. figure:: ../Images/manual_html_m65f5db8f.png
   :alt:

You can download and install the extension which ships with the
OpenOffice (.sxw) manual. In this case, you would not get an new
module or function, just the document itself which you can download in
the loaded list view.

.. figure:: ../Images/manual_html_3cd9b3b7.png
   :alt:

**Extension security**

Please keep in mind, that there is no security audit available for the
extensions, so take a close look at extensions you are installing. If
you find a security issue, get in touch with the security team
(security@typo3.org).


.. toctree::
   :maxdepth: 5
   :titlesonly:
   :glob:

   ChangingBackendLanguage/Index