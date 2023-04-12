# Picgo-config-file
A config file using github as picBed，with CDN and rename function.

## Plugin install

You need to install picgo-plugin-github-plus and picgo-plugin-rename-file plugin before using.

## Config file

Linux and macOS's config file location is `~/.picgo/config.json`.

Windows is `C:\Users\username\.picgo\config.json`.

Copy config.json file to your picgo config location, and change the username / reponame / port in this config file.

## Verification

Copy an image to clipboard and run following command to upload your image.

`picgo u`

You will get output like this which means you have correctly configured picgo.

>(ptgpu) PS C:\Users\Ryushane> picgo u
>
>[PicGo INFO]: Before transform
>
>[PicGo INFO]: Transforming... Current transformer is [path]
>
>[PicGo INFO]: Before upload
>
>[PicGo INFO]: beforeUploadPlugins: rename-file running
>
>[PicGo INFO]: Uploading... Current uploader is [github]
>
>[PicGo SUCCESS]:
>
>https://cdn.jsdelivr.net/gh/Ryushane/PicGo_Pictures/img/2023/04/12/waifu2x_17-18-48.png
