# Staff Search

Fuzzy search an LDAP schema in Drupal 7.
Features include

- filtering out non-staff employees such as City of Boston colleagues,
- reconstructing staff portraits from raw binary streams,
- placing a Block in the sidebar,
- rendering contact info in a View,
- calculating Levenshtein distances for imperfect hits using an improved algorithm called Leventhal,
- and integrating jQuery UI autocomplete.

Please refer to the DocBlocks in [staffsearch.module](staffsearch.module) for usage information.
Each function is documented there, and the functions are organized by their purpose.
