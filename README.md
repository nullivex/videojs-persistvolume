# videojs-persistvolume

A plugin for Video.js that saves user's volume setting using [localStorage](https://developer.mozilla.org/en-US/docs/Web/Guide/API/DOM/Storage#localStorage), but falls back to cookies if necessary.

### Usage
Include the plugin:

```
<script src="videojs.persistvolume.js"></script>
```

Add persistVolume to plugins object with one option, namespace.

    plugins: {
	    persistvolume: {
		    namespace: 'So-Viral-So-Hot'
	    }
    }

## Changelog

### 0.2.0
* Fix compatibility with Video.JS 6 to not throw warnings
* Initial release from Nullivex

### 0.1.3p1
* Final release from `jbboehr/videojs-persistvolume`
