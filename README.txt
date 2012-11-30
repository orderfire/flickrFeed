flickrPhotos is a quick sample application that sends a url request to flickr's public feed, parses the XML and downloads images at the specified URLs.  Thumbnails are generated and displayed via a UICollectionView (grid).  User can select an image to view the full image

Interesting technical implementations:
    Generate thumbnail from image
    Asynchronous image download (throttle via queue)
    SyncManager Delegation 
    Extract image metadata from XML

App still requires polish, refinement & cleanup if we were to release to the app store.
App is missing: cache cleanup, thumbnail / image deletion, API failure handling & more  
This is intended as a code sample
