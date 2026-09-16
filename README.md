Caution:
RDD is discontinued, and many forks contain code that download non official roblox files while claiming they are needed, which is simply not true
SRC.zip has a fixed version of ./src, as i just forked this from the original backup (which was semi broken)
feel free to replace jszip bundle if you dont trust it

enjoy, <3




What is this?
RDD can assemble plain resources directly from Roblox's setup S3 storage bucket into a format the user would expect to be able to directly extract/run from. Everything is fetched locally in your browser, without any additional required server resources!

Usage
[*] USAGE: https://rdd.latte.to/?channel=<CHANNEL_NAME>&binaryType=<BINARY_TYPE>&version=<VERSION_HASH>

    Binary Types:
    * WindowsPlayer
    * WindowsStudio64
    * MacPlayer
    * MacStudio

    Extra Notes:
    * If `channel` isn't provided, it will default to "LIVE" (the production channel)

    You can also use an extra query argument we provide, `blobDir`, for specifying
    where RDD should fetch deployment files from. This is useful for using different
    relative directories than normal for a certain client type, such as for fetching
    stuff from /mac/arm64/ instead of /mac/

    Blob Directories (Examples):
    * "/" (Default for WindowsPlayer/WindowsStudio64)
    * "/mac/" (Default for MacPlayer/MacStudio)
    * "/mac/arm64/"
    ..
Extras
JSZip (Used for WindowsPlayer/WindowsStudio file extraction/generation)
https://github.com/latte-soft/channel-tracker
License
See file: LICENSE

MIT License

Copyright (c) 2024-2025 Latte Softworks <https://latte.to>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
