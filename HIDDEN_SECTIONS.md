# Hidden Sections

Sections currently hidden from the live site but preserved in source.
Any agent can find them by searching the repo for `HIDDEN-` markers.

| ID | File | Status | Hidden On |
|---|---|---|---|
| `HIDDEN-VIDEO-TESTIMONIALS` | `index.html` | hidden via HTML comment wrapper | 2026-05-19 |

## How to restore a hidden section

1. Open the file listed above.
2. Locate the markers: `HIDDEN-<NAME>-START` and `HIDDEN-<NAME>-END`.
   - `grep -n "HIDDEN-VIDEO-TESTIMONIALS" index.html`
3. Delete the opening `<!--` immediately before `HIDDEN-<NAME>-START`
   and the closing `-->` immediately after `HIDDEN-<NAME>-END`.
4. Optionally remove the explanatory header comment block that sits
   right above the wrapper (the one starting with `HIDDEN-SECTION ::`).
5. Delete the row from this table once the section is live again.

## How to hide a new section

Wrap the section like this — pick a unique `HIDDEN-XXX` name and add a
row to the table above:

```html
<!-- ============================================================
     HIDDEN-SECTION :: descriptive-name  (hidden YYYY-MM-DD)
     Short reason / restore notes.
     Grep marker: HIDDEN-DESCRIPTIVE-NAME
     ============================================================ -->
<!-- HIDDEN-DESCRIPTIVE-NAME-START
  ...original section HTML here...
  HIDDEN-DESCRIPTIVE-NAME-END -->
```

Note: do not nest other HTML comments (`<!-- ... -->`) inside the wrapper,
and avoid any literal `--` sequence in the content — both would
prematurely close the outer comment.
