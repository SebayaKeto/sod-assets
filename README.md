# State of Deliverance — CFX server banners

Static assets served via jsDelivr CDN (never expires, no timeouts).

| file | size | slot |
|------|------|------|
| `banner_connecting.jpg` | 1920x1080, ~341KB | `banner_connecting` (connecting screen) |
| `banner_detail.jpg`     | 1920x1080, ~341KB | `banner_detail` (server-list detail card) |

## jsDelivr URLs (once pushed to GitHub as a PUBLIC repo)
Pattern: `https://cdn.jsdelivr.net/gh/SebayaKeto/<REPO>@<BRANCH>/<file>`

Example (replace SebayaKeto with your GitHub username, repo `sod-assets`, branch `main`):
- https://cdn.jsdelivr.net/gh/SebayaKeto/sod-assets@main/banner_connecting.jpg
- https://cdn.jsdelivr.net/gh/SebayaKeto/sod-assets@main/banner_detail.jpg

## server.cfg
```
sets banner_connecting "https://cdn.jsdelivr.net/gh/SebayaKeto/sod-assets@main/banner_connecting.jpg"
sets banner_detail     "https://cdn.jsdelivr.net/gh/SebayaKeto/sod-assets@main/banner_detail.jpg"
```
