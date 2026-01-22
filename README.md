# Outlook Email Signature

This repo contains an Outlook-friendly HTML signature built from the provided
design. The layout uses tables and inline styles to render consistently in the
latest Microsoft Outlook desktop clients.

## Files

- `signature.html` - the signature markup
- `images/signature-left.jpg` - left-side photo + logos (280x233 px)
- `images/icon-facebook.png` - 14x14 px
- `images/icon-instagram.png` - 14x14 px

## How to use in Outlook (Windows desktop)

1. In Outlook, go to **File > Options > Mail > Signatures** and create a new
   signature (this generates the signature folder).
2. Open `%APPDATA%\Microsoft\Signatures`.
3. Replace the generated `.htm` file with `signature.html` (keep the same file
   name as your signature).
4. Create an `images` folder next to the `.htm` file and place the images listed
   above inside it.
5. Make sure the image filenames match exactly what `signature.html` expects.

If you prefer a different folder name, update the `src` paths in
`signature.html` to match.
