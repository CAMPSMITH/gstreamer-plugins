# gstreamer-plugins

A repository of plugins for Gstreamer


## Sample filter 
```
/Library/Frameworks/GStreamer.framework/Versions/Current/bin/gst-launch-1.0 \
    videotestsrc ! circleAR ! osxvideosink
```

## Inspecting plugin
```
/Library/Frameworks/GStreamer.framework/Versions/Current/bin/gst-inspect-1.0 \
    circleAR \
    --gst-plugin-path=$PWD/build/
    
```