# Alumni Association of NUTC-CSIE
Static blog source code for Alumni Association of NUTC-CSIE.

## Contributing
All kinds of contributions (new post, documentation & code improvements, issues & bugs reporting & new design) are welcome.

## Quick Start
First, download [Node.js](https://nodejs.org/en/) and install Hexo in your computer:
```sh
$ npm install hexo-cli -g
```

Get source code from GitHub, and install packages afterwards:
```sh
$ git clone https://github.com/nutc-csie/nc-static-blog.git
$ cd nc-static-blog
$ npm install
```

Now you can modify source to improve blog, and then type the following command to preview your changed:
```sh
$ hexo server

INFO  Start processing
INFO  Hexo is running at http://localhost:4000/. Press Ctrl+C to stop.
```

If everything is ready, just deploy to github.io:
```sh
$ ./quick-deploy <your_branch_name>
```

Finally, pull a request to master.
