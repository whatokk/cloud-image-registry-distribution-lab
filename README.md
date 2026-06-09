# Cloud Image Registry & Distribution Lab

This repository contains the files for Lab 03.

The GitHub Actions workflow builds two versions of an Nginx web application, pushes both versions to GitHub Container Registry, performs a clean-room pull test, reproduces a port conflict on port 8888, solves it by changing/removing the occupied port, and compares standard Nginx with Alpine Nginx image sizes.

Main package:

`ghcr.io/whatokk/cloud-app`
