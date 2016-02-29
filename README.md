# ClassTracks™

ClassTracks is a trademarked name and all content, IP, and creative in this repository is a Copyright of ClassTracks and should not be used or copied without explicit permission from ClassTracks.

## Installation
1. Follow the instructions at [classtracks/vm](https://bitbucket.org/classtracks/vm)
2. `cd classtracks`
3. `git clone git@bitbucket.org:classtracks/myclasstracks.com.git`
4. `cd vm`
5. Run
    * `vagrant reload` if the vagrant machine is already running, OR
    * `vagrant up` if it has stopped
6. `vagrant ssh -c 'cd /classtracks/myclasstracks.com; jekyll serve --host 0.0.0.0'`
    * Since this command will be used frequently, add this to an aliases file: `alias ctsite='vagrant ssh -c "cd /classtracks/myclasstracks.com; jekyll serve --host 0.0.0.0"'`
    * Then just run `ctsite` instead
7. Run `vagrant halt` when you have finished coding for the day

## Deployment
1. Install [AWS Command Line Interface](https://aws.amazon.com/cli/)
2. Ask any developer to email you the AWS CLI config file.
3. Copy the config file `~/.aws/config`
4. `cd _site/`
5. `aws s3 cp ./ s3://www.myclasstracks.com/ --recursive --exclude ".git/*"`
