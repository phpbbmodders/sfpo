# Bugs

## Reports from the extension audit

### Undefined sfpo_posts_to_show warning

Reproduce the missing forum setting and check schema, migration history and row loading before deciding how to handle the missing key. [Source](https://www.phpbb.com/customise/db/extension/show_first_post_only_to_guest/support/topic/252448)

### HTML fragment parsing can warn on video attachments

Verify guest rendering of valid video and source elements. Warning suppression does not establish that truncated output is correct. [Source](https://www.phpbb.com/customise/db/extension/show_first_post_only_to_guest/support/topic/251971)
