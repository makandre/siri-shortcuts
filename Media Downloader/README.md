# Media Downloader

This [shortcut](Media%20Downloader.shortcut) is a refactor of the [Media Downloader](https://www.icloud.com/shortcuts/00d0076176854dc083c2067e30bd543f) that is described at https://blogtip.org/how-to-download-youtube-facebook-videos-on-iphone

The shortcut will now use separate downloader shortcuts to download media from different sites.  The following downloaders are available:

- [YouTube](YouTube%20Downloader.shortcut) - based on steps from the original Media Downloader
- [Facebook](Facebook%20Downloader.shortcut) - based on steps from the original Media Downloader
- [Twitter](Twitter%20Downloader.shortcut) - based on this [shortcut](https://www.icloud.com/shortcuts/e5f06ab2d11c4837adc40944900f6ca8) created by u/freelancedev_ [here](https://www.reddit.com/r/shortcuts/comments/9o0qxb/twitter_video_downloader_v15/)
- [Reddit](Reddit%20Downloader.shortcut) (with sound) - based on this [shortcut](https://www.icloud.com/shortcuts/95bf85ad02214cd98dd746b3c2d2d4dd) created by u/back1n7ime [here](https://www.reddit.com/r/shortcuts/comments/9nokci/download_reddit_videos_with_sound/)
- [Other](Content%20Downloader.shortcut) - a catch-all option to download the contents of the input URL directly (for example, use this option with the [YouTube To MP3](../YouTube%20To%20MP3) shortcut)

After downloading the file, you will also have the option to convert it to M4A audio format (if applicable).

## Run Individual Downloader Shortcuts

If you want to use the downloaders on their own, you will need to do the following:

1. Re-enable showing the shortcut in the Share Sheet and choose URL as the input type
2. Add a final step to save or share the downloaded file

## When It Doesn't Work...

Sometimes the Media Downloader (more specifically the YouTube Downloader) doesn't work on a particular YouTube video.  If all you want is the audio, you can try the aforementioned [YouTube To MP3](../YouTube%20To%20MP3) shortcut with the `Other` option.

For video, try this workaround:

1. If not in Safari, first use the [Open In Safari](../Miscellaneous/Open%20In%20Safari.shortcut) shortcut to open the video in Safari
2. Use the [Background YouTube](../Miscellaneous/Background%20YouTube.shortcut) shortcut, which stops the video.  When you resume it and it will start playing in a full screen playback window
3. Press `X` on the upper left to close the playback window
4. Now share the video to the Media Downloader shortcut and use the `Other` option to capture it
