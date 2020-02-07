# UML Designer (Technische Universität Ilmenau's branch)
A modified version of the graphical tooling to edit and visualize UML models "UML Designer".

Update site: https://sse.tu-ilmenau.de/umldesigner-update

## Installation note:
Third party software 'Sirius Project' as well 'org.eclipse.amalgam' is not completely provided by eclipse update site.
Thus, following update sites must be added to eclipse installation before installing UML Designer.
- https://download.eclipse.org/sirius/updates/releases/6.2.2/2019-06/
- https://download.eclipse.org/modeling/amalgam/updates/stable/1.9.2-S20181203/capella/


## What are the differences between this branch and the original one?
### Enhancements
- Support for Eclipse 2019-06
- Support for Sirius 6.2.2
- Added support for DataStore and CentralBuffer nodes
- Added support for several Actions

### Fixes
- Remove the restriction for the operation selection during the CallOperationAction creation

### Graphical Preferences
These changes make it easier to export diagrams in a higher quality format for black and white printing:
- The diagrams are displayed in black and white and icons are hidden
- Labels on control nodes are hidden by default
- Multiplicity from attributes has been hidden
- SVG representation for some nodes (e.g. final, initial nodes), instead of the PNG raster format

# Welcome to UML Modeling by Obeo Network

UML Designer provides a set of common diagrams to work with UML 2.5 models. The intent is to provide an easy way to make the transition from UML to domain specific modeling. This way users can continue to manipulate legacy UML models and start working with DSL. Users can even re-use the provided representations and work in a total transparence on both UML and DSL models at the same time.

These plugins are released under the EPL Open-Source License.

Visit our web site : http://www.umldesigner.org
