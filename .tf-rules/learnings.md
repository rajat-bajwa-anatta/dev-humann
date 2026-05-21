## Recent
[chat] Announcement bar utility links must be in-flow flex siblings of the slider, NOT position:absolute — absolute positioning causes overlap with arrows on viewports narrower than ~1200px
[chat] place-content on a block-level custom element (slideshow-slide) has no effect — use display:flex + align-items:center + justify-content:center on the slide itself to center content
[chat] Inline --line-height:1 on announcement block overrides theme variables — if text wraps to multiple lines on mobile, line-height:1 compresses lines; set via typography-style or explicit CSS instead
[chat] slideshow-arrows uses position:absolute; inset:0 by default — within a flex:1 slider container the arrows will correctly stay within the slider bounds without needing an explicit width constraint
[chat] _announcement block: button_text/button_link/link settings removed — links are now added inline via the inline_richtext text field editor (supports <a>, <u>, <b>, <i>)
[chat] header-group.json announcement text uses inline HTML: "Free Shipping on orders $49.99+ <u>Shop now</u>" — the inline_richtext field type renders this correctly
