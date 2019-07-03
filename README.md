# CSV Fingerprint

CSV Fingerprint is a small app that generates qualitative visualizations of any
CSV file to help debug any formatting issues. Each cell is colored
according to its type. Yellow for strings, blue for integers, purple for
decimals and gray for empty values.

# Installation

First, clone the repo using git.

    git clone git://github.com/setosa/csv-fingerprint


Next, from the terminal, run the following command from within the project
directory.

    python -m SimpleHTTPServer

For python3, we need to use:

    python3 -m http.server 9000

This will start a webserver running where you can access the app from a browser
using the following url:

    http://localhost:8000

For python3:
    http://0.0.0.0:9000/

