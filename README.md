# java-cli-buildr-ssl-postgresql-simple

## Description
A java buildr build, that connects to postgresql database.

Uses self-sign ssl.

## Tech stack
- java
- buildr
  - 6.8.2

## Docker stack
- alpine:edge
- postgresql:alpine
- vanto/apache-buildr:latest-jruby-jdk8

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
