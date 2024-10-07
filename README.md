

# ChatGPT Reading Speed Control Bookmarks 📖⚡⏩

This README guide will show you how to create bookmarks in your browser that allow you to increase, decrease, or reset the playback speed of ChatGPT's reading feature. By utilizing JavaScript code injected directly from your browser bookmarks, you can easily modify the speed at which the content is read aloud.

## Introduction 🌟

These bookmarklets are simple pieces of JavaScript code that modify the `playbackRate` of audio elements on the page. With these, you can:

- Decrease the reading speed by 0.25 increments.
- Reset the speed to the default value (1x).
- Increase the reading speed by 0.25 increments.

Bookmarklets are easy to use and provide a convenient way to control playback without needing any extra extensions or settings.

## Creating the Bookmarks ✨

Follow these steps to create bookmarks in your browser that allow you to control the reading speed:

1. Open your browser's bookmarks or favorites manager.
2. Create a new bookmark.
3. Name the bookmark appropriately (e.g., "Decrease Speed", "Reset Speed", or "Increase Speed").
4. Copy one of the JavaScript codes provided below and paste it into the **URL** or **Address** field of the bookmark.

Now you can use these bookmarks whenever ChatGPT is reading aloud—just click the bookmark to adjust the speed.

## Available Controls 🎛️

### -0.25 Speed

This bookmark decreases the playback speed by 0.25x.

```
javascript:(function(){document.querySelector('audio').playbackRate-=0.25;})();
```

**How it works**: This code locates the `audio` element on the page and decreases its `playbackRate` by 0.25. Use it if you find the reading speed too fast and want a slower pace.

### Reset to Normal Speed (1x)

This bookmark resets the playback speed back to the default value of 1x.

```
javascript:(function(){document.querySelector('audio').playbackRate=1;})();
```

**How it works**: This code sets the `playbackRate` of the `audio` element to `1`, which is the normal speed. Use it if you want to return to the default speed after making adjustments.

### +0.25 Speed

This bookmark increases the playback speed by 0.25x.

```
javascript:(function(){document.querySelector('audio').playbackRate+=0.25;})();
```

**How it works**: This code locates the `audio` element and increases its `playbackRate` by 0.25. Use this if you want to speed up the reading.

## Notes 📝

- These bookmarks rely on there being an `audio` element on the page that is currently playing. Make sure the page is actively reading something aloud before using the bookmarks.
- Bookmarklets may not work in every browser or situation due to content security policies or certain page restrictions. If the bookmarklet doesn't work, consider checking your browser's console for errors or trying another browser.

😊🎧 Happy listening!
