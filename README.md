# minifs

When I am building machines with Vagrant and the like I have to get files from remote services to make the installation work. When I have limited network connectivity, or even none this will allow me to host the files myself and the scripts will just download them from me

## Usage

    $ minifs --host localhost --port 8080 --dir /tmp

This will listed to `localhost` on port `8080` and server up any file requested if it is available in `/tmp`

