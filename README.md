# ClassTracks™

Class Tracks is a trademarked name and all content, IP, and creative in this repository is a Copyright of CLassTracks and should not be used or copied without explicit permission from ClassTracks.

## Deploying
  1. Install AWS Command Line Interface
  2. `cd _site/`
  3. `aws s3 cp ./ s3://www.myclasstracks.com/ --recursive --exclude ".git/*"`
