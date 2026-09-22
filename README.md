# YJ Furniture portfolio

Photos are separate files in images/. index.html is the customer site; editor.html is the editing tool.

## Add photos and publish

1. Open https://lengfei03-droid.github.io/YJFurniture/editor.html in your usual browser.
2. Click Edit website, add projects and photos, and Save changes.
3. Click Export website ZIP. Keep the ZIP as a backup.
4. Unzip it. Upload index.html, editor.html and the images folder into this repository root. Do not upload the ZIP or its outer folder.
5. Commit changes and wait for GitHub Pages to deploy.

For large collections, upload images in batches inside images/ first, then upload the HTML files last. Reuse generated filenames.

## Storage

New photos are compressed to WebP at up to 1600 pixels. Drafts and photo blobs use IndexedDB instead of localStorage. The editor starts from the matching published content. Drafts are saved separately for each published version, so outdated drafts cannot replace a new version. Previous IndexedDB drafts and the original localStorage copy are retained on the same device.

Browser storage is not unlimited and can be cleared. Keep ZIP backups. Edits remain device-local until you upload the exported files. The editor does not grant repository write access and is not an authenticated admin panel. Customers see only published data.

## 中文操作

打开在线编辑页面 → 添加照片并保存 → Export website ZIP → 解压 → 将网页文件和 images 文件夹上传到仓库根目录。图片很多时先分批上传图片，最后更新网页。保留 ZIP 备份，不要只依赖浏览器储存。

