# notebooks

## Usage

`git clone https://github.com/andrewwhitehouse/notebooks.git`

`cd notebooks`

`docker run -d -p 8888:8888 -v $PWD:/home/jovyan/notebooks \
                           --rm andrewwhitehouse/clojupyter-nodejs-docker:0.4.3`
                          
`docker logs <container id>` to get token

Browse to localhost:8888 and enter the token output above.                         


Copyright (c) Andrew Whitehouse 2021. See LICENSE for terms of use.
