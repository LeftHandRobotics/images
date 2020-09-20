# Images

Source and output files for art assets. Also includes some scripts to make it faster to save images from layers for most of our documents. We are using RawGit as a CDN for image hosting. This allows us to serve our images directly from GitHub.

## Exporting

The contents of `scripts` can make your life a lot easier when working with composite illustrator or photoshop files. 

To resave all layers automatically in Illustrator:

- Click on File > Scripts > Other and select `ai-layer-exporter.jsx` from this scripts directory in this repo 
- Set the output directory and click "Export"

### Base Paths
- Production: https://cdn.rawgit.com/LeftHandRobotics/images/master/images/
- Development: https://rawgit.com/LeftHandRobotics/images/master/images/