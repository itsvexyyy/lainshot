# lainshot
[![WTFPL](http://www.wtfpl.net/wp-content/uploads/2012/12/wtfpl-badge-4.png)](http://wtfpl.net/)\
**Command Line ShareX Wannabe**


## Usage
Default uploader: [pomf.lain.la](https://pomf.lain.la)\
Default URL shortener: [love-la.in](https://love-la.in)

Running `lainshot` with no options defaults to `lainshot -a -s`, which will screenshot the active window and save it. In most cases, pictures are saved to `~/Pictures/Screenshots` by default, which will be created if it does not exist.

### Options
**Screenshot type**
- `-a`/`--active-window` - Screenshot the active window
- `-r`/`--region` - Manually select a region to capture

**Saving/uploading**
- `-d DIR`/`--dir DIR` - Specify a directory to save the screenshot in
- `-s`/`--save-only` - Save the screenshot locally without uploading it
- `-p`/`--upload-only` - Upload the screenshot and delete the local file
- `-u`/`--upload` - Upload the screenshot and save it locally
- `-l`/`--shortlink` - Generate and output a shortlink after uploading

**Output**\
By default, the script outputs either the file name or URL to `stdout`.
- `-c`/`--clipboard` - Copies the output to the KDE Klipper clipboard, if available, **in addition to** `stdout`.


## Future plans
- Custom uploader/shortener support
- Support a wider array of screenshot utilities

_made with love by vexyyy_
