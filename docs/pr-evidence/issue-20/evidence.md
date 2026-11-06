# Issue #20: terminal evidence

The before screenshots have one black rectangle covering the local account path. All pixels outside the rectangle are unchanged. The fixed screenshots are unchanged copies.

| Action | Before | Fixed |
| --- | --- | --- |
| Backspace during reverse search | [Query stays `tot`, command loses `;`](old-backspace.png) | [Query becomes `to`, command keeps `;`](fixed-backspace.png) |
| Esc during reverse search | [Search remains visible](old-escape.png) | [Normal prompt returns](fixed-escape.png) |
| Continue editing after Esc | | [Typed ` // ESC_OK` at the normal prompt](fixed-escape-editing.png) |
