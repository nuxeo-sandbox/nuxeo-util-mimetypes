# nuxeo-util-mimetypes

An element for dealing with MIME types, file extensions, and (optionally) friendly file names.

## Requirements

Install Node.js (I use Homebrew)

Navigate to the folder containing `nuxeo-util-mimetypes.html` in shell/terminal and then:

    npm install -g polyserve
    npm install -g bower
    bower install

## Usage

You can run it via `polyserve` but you may need to make a few changes:

* Edit `demo/index.html` and modify the `<nuxeo-connection>` element with the URL for the server. For example:
  * `<nuxeo-connection url="http://localhost:8080/nuxeo"></nuxeo-connection>` (default).
  * The user name and password can be included here as well. See the [`nuxeo-elements` documentation](https://doc.nuxeo.com/x/XJCRAQ).

Then run it:

    polyserve -p 3000

Once running, you can checkout the demo at `http://localhost:3000/components/nuxeo-util-mimetypes/demo`.

## About Nuxeo

Nuxeo dramatically improves how content-based applications are built, managed and deployed, making customers more agile, innovative and successful. Nuxeo provides a next generation, enterprise ready platform for building traditional and cutting-edge content oriented applications. Combining a powerful application development environment with SaaS-based tools and a modular architecture, the Nuxeo Platform and Products provide clear business value to some of the most recognizable brands including Verizon, Electronic Arts, Netflix, Sharp, FICO, the U.S. Navy, and Boeing. Nuxeo is headquartered in New York and Paris. More information is available at [www.nuxeo.com](http://www.nuxeo.com).