# Permanent Community Builds gallery

This archive is independent of episode promotions. Preserve the `#community-builds` section, navigation link, gallery assets, and existing builder entries when rotating episodes.

## Add another build

1. Create a stable folder here for the builder/build; include large images and lightweight thumbnails.
2. Append a new `article.community-build` inside `#community-builds .wrap` in `index.html`. Keep all previous entries.
3. Give the article a unique anchor, builder credit, build number, short factual description, and photo count.
4. Give its `.guest-photo-grid` a unique `data-photo-gallery` and descriptive `data-gallery-label`.
5. Each `.guest-photo` links to its large image and includes a thumbnail with descriptive alt text and `data-caption`. The shared viewer automatically limits next/previous navigation to that build.
6. Check mobile layout, image loading, keyboard navigation, Escape, focus restoration, and that episode galleries stay separate.

First entry: David “D.C.” Callari from GPStar, 15 user-supplied photos, added October 10, 2026 and expanded October 17, 2026.

Second entry: Jeff Keenan & the Massachusetts Ghostbusters, 15 unique photos. Thirteen photos live in `community-builds/massachusetts/`; two existing photos are shared from `massachusetts-gallery/`. Preserve both asset folders during episode rotations. The episode and permanent galleries intentionally reference the same files; do not add duplicate cards within a gallery.
