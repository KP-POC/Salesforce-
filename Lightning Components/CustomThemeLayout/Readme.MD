* a theme layout component must implement the forceCommunity:themeLayout interface.
* Add {!v.body} wherever you want the content, which changes from page to page, to appear within the theme layout.
* Attributes declared as Aura.Component[] and included in your markup are rendered in the theme layout as open regions, which form the basic structure of your theme layout. Users can add drag-and-drop components to these regions in Community Builder.
* The tokens bundle extends forceCommunity:base, which gives you access to all the tokens exposed by SLDS and the branding values defined in the Branding panel in Community Builder.
