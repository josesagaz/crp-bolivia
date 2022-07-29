+++
###############################################################################
#
# estas noticias tienen que ser guardados en el folder 'videos'
#
###############################################################################

# A Recent Blog Posts section created with the Pages widget.
# This section displays recent blog posts from `content/post/`.

widget   = "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true          # This file represents a page section.
active   = true          # Activate this widget? true/false
weight   = 85            # Order that this section will appear.

title = "Videos"
subtitle = "Seleccion de materiales"

[content]
  # Page type to display. E.g. post, talk, or publication.
  page_type = "videos"
  filter_default = 0
  
  [[content.filter_button]]
    name = "Todos"
    tag = "*"
  
  [[content.filter_button]]
    name = "¿QUE ES LA OTAN?"
    tag = "OTAN"
  
  [[content.filter_button]]
  name = "Consecuencias de la guerra"
    tag = "Consecuencias"
    
[[content.filter_button]]
  name = "Crisis del sistema universitario"
    tag = "Crisis"

[[content.filter_button]]
  name = "El pedigri jailon"
    tag = "El_pedigri"

[[content.filter_button]]
  name = "Autoritarismo en Colombia?"
    tag = "El_fin"
    
[[content.filter_button]]
  name = "La COB en la historia"
    tag = "La_COB"
    
[[content.filter_button]]
  name = "Cumbre de la OEA"
    tag = "OEA"

[[content.filter_button]]
  name = "Policia Boliviana"
    tag = "la_policia"

[[content.filter_button]]
  name = "Los Medios"
    tag = "medios"



  # Filter posts by a taxonomy term.
  [content.filters]
    tag = ""
    category = ""
    publication_type = ""
    author = ""
    exclude_featured = false
  
[design]
  columns = "2"
  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)
  view = 5
  flip_alt_rows = true
  
[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.
  
  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.
    image = "back3.jpg"  # Name of image in `static/img/`.
    image_darken = 0.3     # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque..

  # Text color (true=light or false=dark).
  text_color_light = false  
  
[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++
