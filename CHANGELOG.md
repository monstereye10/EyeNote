# EyeNote Changelog

## 2.1.1

- Bug fixes and crash fixes.

## 2.0.10

- Built a new Windows installer.
- Updated the installer agreement.
- Improved EyeNote Documents so they work as boards instead of a separate app.
- Added document pages, rich text tools, custom fonts, text sizes, text color, highlight color, letter spacing, paragraph tools, document images, and document exports.
- Improved document spell check with a bottom toggle, better common-word suggestions, lower red underlines, faster right-click suggestions, and one-click corrections.
- Fixed document formatting so font, size, bold, paragraph settings, text color, and highlight color stay active while typing and do not snap back to nearby text.
- Fixed document delete, selection, copy, paste, right-click menu behavior, pasted images, dragged-in images, image resizing, and image aspect ratio.
- Added document export formats: PDF, plain text, Markdown, HTML, and EyeNote document files.
- Fixed EyeNote document export/import so document files keep their title and open as a new document inside the current EyeNote window.
- Added board export formats: EyeNote board, JSON, Markdown, and HTML.
- Fixed EyeNote board export/import so shared board files keep titles, include needed assets, and import inside the current EyeNote window.
- Removed the PDF importer after testing because it did not fit the document workflow.
- Improved board and document sidebar rows with bigger click areas, drag handles, delete controls, right-click menus, copy/paste shortcuts, optional icons, remove-icon action, and cleaner spacing.
- Fixed board/document sidebar dragging so rows lift up, reorder in place, stay inside the Boards section, and do not leave stuck gray click bars.
- Reworked board and document row effects so they look closer to the app buttons and apply to the row that was clicked.
- Redesigned board customization with a larger window-width menu, cleaner layout, simpler preview, effects on the left, saved color presets, custom colors, background image tiling, and working board line controls.
- Removed the broken RGB sliders from board customization.
- Improved image cards with clean image mode, no border/background/effects in clean mode, no trash icon in clean mode, and Delete in the image right-click menu.
- Integrated effect colors into card effects.
- Moved the Relationship Map section above Drawing.
- Improved custom app logos, logo color saving, logo presets, circular uploaded logos, and matching taskbar/home-screen icons.
- Reduced startup delay by showing local boards first and delaying cloud, font, spellcheck, file-link, and sound setup until after the app opens.
- Fixed a Windows crash path tied to Flutter's accessibility tree by rebuilding EyeNote on a newer Flutter engine.
- Reduced startup freezes by moving the large spell-check dictionary setup off the first app open.
- Lowered idle CPU from animated card effects by keeping text, media, and controls out of every animation repaint.
- Reduced extra startup work from sound effects by loading sound players only when a sound is actually played.
- Improved document spell-check ranking so short common corrections like "well" win over obscure words, and made red-underlined words open a direct spell menu from the first right-click.
- Added the Cancel Premium link to the Premium area.
- Added separate Premium and Cancel Premium buttons in settings, and made board card dragging redraw faster while moving apps.
- Changed EyeNote Premium buttons to open /premium and made the Warning logo preset use the full bundled logo source.
- Made sub-board cards solid again and gave their open target a bigger hitbox.
- Updated Premium to $1.99/month across the app and website.
- Added support, admin, cancel Premium, install help, privacy updates, better website download links, and fuller release notes.

## 2.0.9

- Bug fixes.
- Changed Premium to $1.99/month.
- Added the new Premium Document feature.
