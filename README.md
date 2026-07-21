iec-apt-repo is a private apt repository.
Before your push the kernel packages, you need to generate Packages.gz firstly by
"sudo dpkg-scanpackages . /dev/null | gzip -9c | sudo tee Packages.gz > /dev/null".
And also push Packages.gz to iec-apt-repo.
