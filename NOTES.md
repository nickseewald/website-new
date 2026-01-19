# Notes detailing modifications to the stock template

- Modified
  [get_author_profile.html](layouts/_partials/functions/get_author_profile.html)
  to additionally create `highlight` and `lab_member` elements of the profile
  that track whether to style certain authors in author lists.
- Modified [page_author.html](layouts/_partials/page_author.html) to only print
  the author card for pages that have data.
- Modified
  [page_metadata_authors.html](layouts/_partials/page_metadata_authors.html) to
  only link to authors with available pages (i.e., lab members)
- Modified [single.html](/layouts/single.html) to put commas in the same div as
  author name (i.e., the div is now author-name, vs. , author-name).