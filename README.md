# Configuration to provide custom PostgreSQL version on Travis CI job

This project aims to provide a custom Travis CI configuration that lets users 
to use custom PostgreSQL version within their Travis CI job. While sometimes 
it is struggle to manage custom database versions on Travis CI, it is actually 
simple as using `apt` packages and putting a bit more changes on the default 
PostgreSQL configuration files.
