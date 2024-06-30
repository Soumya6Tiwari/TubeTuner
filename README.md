# TubeTuner

TubeTuner is a robust Chrome extension crafted to elevate your YouTube journey. It empowers you to effortlessly bookmark precise timestamps within videos, whether you're diving into educational content, tutorials, or entertainment. TubeTuner ensures that significant moments are saved for quick retrieval, eliminating the need to scrub through videos. Simply jump directly to the moments that hold the most value to you.


# Screenshots

*image of TubeTuner Chrome Extension*
![image of TubeTuner Chrome Extension](https://github.com/Soumya6Tiwari/TubeTuner/blob/ab30b76b89da15845d3f09f519adbf318e8d3717/screenshots/image%20of%20TubeTuner%20Chrome%20Extension.png)<br><br><br>




*Non Youtube video page*
![](https://github.com/Soumya6Tiwari/TubeTuner/blob/f8fe9f11df3baaecfd70a75b0cd7cfa4f59d733c/screenshots/Non%20Youtube%20Video%20page.png)
<br><br><br>




*Without Bookmarks*
![Without Bookmarks](https://github.com/Soumya6Tiwari/TubeTuner/blob/f8fe9f11df3baaecfd70a75b0cd7cfa4f59d733c/screenshots/Without%20Bookmarks.png)
<br><br><br>

*Bookmarks*

![](https://github.com/Soumya6Tiwari/TubeTuner/blob/eb35809e9d29e920abdd2400cb5a67a186a6e872/screenshots/Bookmarks.png)
<br><br>
![](https://github.com/Soumya6Tiwari/TubeTuner/blob/eb35809e9d29e920abdd2400cb5a67a186a6e872/screenshots/Bookmarks_.png)
<br><br><br>

*Editing and creating a note*
![](https://github.com/Soumya6Tiwari/TubeTuner/blob/eb35809e9d29e920abdd2400cb5a67a186a6e872/screenshots/Editing%20and%20creating%20a%20note%20.png
)
<br><br><br>
*Edited Bookmarks*
![](https://github.com/Soumya6Tiwari/TubeTuner/blob/eb35809e9d29e920abdd2400cb5a67a186a6e872/screenshots/Edited%20Bookmarks.png)
<br><br><br>

## Table of Contents
- [Features](#features)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Understanding the Code](#understanding-the-code)
- [Resources](#resources)
- [Support](#support)

## Features

1. Create bookmarks with notes
2. View and manage saved bookmarks
3. Easy navigation to specific timestamps
4. Edit existing bookmarks
5. Delete bookmarks

## Getting Started
Follow these steps to get started

## Prerequisites

- Google Chrome Browser

## Installation
1. [Fork](https://github.com/Soumya6Tiwari/TubeTuner) and then clone this repository

3. Open Google Chrome.
4. Go to `chrome://extensions/`.
5. Enable "Developer mode" in the top-right corner.
6. Click "Load unpacked extension" and choose the folder where you saved the cloned repository.

The extension should now appear in your Chrome toolbar.

## Usage

1. Open a YouTube video.
2. Click on the ("+") icon below the video to create a bookmark. 
3. Click on the TubeTuner icon in your Chrome toolbar to access your saved bookmarks.
4. Add & edit notes for your bookmarks
5. Navigate to specific timestamps.
6. Delete single or all bookmarks.

## Understanding the Code

In this section, the main logic of the extension in the `popup.js` script is explained.

- `showEditModal`: Displays the edit modal for editing the bookmark text.
- `saveEditedNote`: Saves the edited bookmark text.
- `showFullNote`: Displays the full note when the truncated note is clicked.
- `addNewBookmark`: Adds a new bookmark element to the list of bookmarks.
- `viewBookmarks`: Displays all saved bookmarks for the current video.
- `onPlay`: Jumps to the timestamp of the clicked bookmark.
- `onEdit`: Opens the edit modal for the clicked bookmark.
- `onDelete`: Deletes the clicked bookmark.
- `onDeleteAll`: Deletes all bookmarks for the current video.
- `setBookmarkAttributes`: Sets the attributes and event listeners for bookmark controls.

## Resources

- [Chrome Developer Documentation](https://developer.chrome.com/docs/extensions/mv3/)



## Support

If you have any questions or need help getting started, please open an issue in the repository or contact me via email: <a href="mailto:soumyaecc6@gmail.com">soumyaecc6@gmail.com</a>

