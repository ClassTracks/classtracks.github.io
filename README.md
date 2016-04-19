# ClassTracks™

ClassTracks is a trademarked name and all content, IP, and creative in this repository is a Copyright of ClassTracks and should not be used or copied without explicit permission from ClassTracks.

## Installation
1. Follow the instructions at [classtracks/vm](https://bitbucket.org/classtracks/vm)
2. `cd classtracks`
3. `git clone git@github.com:classtracks/classtracks.github.io.git`
4. `cd vm`
5. Run `vagrant up` if it has stopped

## Running It
* Outside the VM
  1. `cd path/to/classtracks/vm`
  2. `ctsite`
    * Be sure to `source` the `aliases.sh` from the [vm](https://bitbucket.org/classtracks/vm) before you do
* Inside the VM (`vagrant ssh`)
  1. `cd classtracks/classtracks.github.io`
  2. `jekyll serve --host 0.0.0.0`
* Run `vagrant halt` when you have finished coding for the day

## Deployment
* On GitHub
  1. Merge a Pull Request into `master`
* On your machine
  1. `git checkout master`
  2. `git push`
