Installation
============

The installing steps are:
-------------------------

- Add collective.amberjack.core collective.amberjack.portlet collective.amberjack.plonetour packages in your buildout.cfg
- Run buildout and (re)start Zope
- Use the quick installer to (re)install the products

buildout.cfg example
--------------------

For basic installation use the following section in your buildout::

    [buildout]
    ...
    eggs =
        ...
        collective.amberjack.core
        collective.amberjack.portlet
        collective.amberjack.plonetour
    
    [instance]
	...
    zcml =
        collective.amberjack.core
        collective.amberjack.portlet
        collective.amberjack.plonetour
