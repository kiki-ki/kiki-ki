# avatars

Avatar images for use as profile icons on various services. Follow the rules below when adding an image.

## Naming

Name files `kiki-<style>[-<variant>].png`, all lowercase kebab-case.

- `<style>`: the overall look of the avatar, such as `formal` or `casual`. Add a new style when an image fits none of the existing ones.
- `<variant>`: added only to tell an image apart from the base image of the same style, such as `pixel` or `transparent`.

The `kiki-` prefix keeps a file recognizable after it is downloaded and used elsewhere.

## Size and format

Every image is a 1024×1024 square PNG.

- PNG keeps transparency and is accepted by every icon upload form. Some services reject WebP.
- 1024px is large enough for the profile icons of major services. Do not upscale a source image smaller than 1024px.
- A transparent image gets the `-transparent` variant. Add a version with a filled background next to it for services that do not handle transparency.
