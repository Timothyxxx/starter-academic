widget: pages
headless: true  # This file represents a page section.

# ... Put Your Section Options Here (title etc.) ...

content:
  # Page type to display. E.g. post, event, or publication.
  page_type: post
  # Choose how much pages you would like to display (0 = all pages)
  count: 5
  # Choose how many pages you would like to offset by
  offset: 0
  # Page order. Descending (desc) or ascending (asc) date.
  order: desc
  # Optionally filter posts by a taxonomy term.
  filters:
    tag: ''
    category: ''
    publication_type: ''
    exclude_featured: false
    exclude_past: false
    exclude_future: false
design:
  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)  
  view: 2