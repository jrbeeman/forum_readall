Super-simple module that allows users to mark all forum threads
as read either globally or for a specific forum.

Gotchas:
- Only works with Drupal 5.x for now
- Provides no UI out of the box. Somewhere in your theme you'll
  need to render links to /forum/readall/%tid where %tid is the
  taxonomy term ID for a given forum, or NULL / 0 to globally
  mark threads as read.
