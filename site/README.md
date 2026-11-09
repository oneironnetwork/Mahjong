# Website copy of the spinner

`site/mahjong/index.html` is a standalone copy of `index.html` for the
oneironnetwork.com site. To publish it at oneironnetwork.com/mahjong, copy it
into the `oneironnetwork/oneironnetwork` repo at `public/mahjong/index.html`.
Vite serves `public/` as-is, so it is not part of the React app, not in the nav,
and it carries `noindex, nofollow` so search engines skip it.

When `index.html` changes, regenerate this copy and copy it over again.
