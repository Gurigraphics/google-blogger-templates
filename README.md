Without this section nothing is shown at all:

    <b:section class='footer' id='footer' preferred='yes'/>

Following widgets are mandatory and shown regardless wheather they are in template:

    Navigation Bar
    Attribution
    Header

To hide them one should use css.

[Minimal template with posts]()

#`Blog1` widget

Includable `post` is mandatory.

Can we invoke `post-index` and `post-item` includables from within `post` includable? That is differend includables regarding to page type -- `index` or `item`. Yes, [this is possible]().

#A widget can only contain b:includable elements.