# Render-test
A basic website -- just enough to test out hooking things up to render, and not much more.

We will go over steps in lecture. You should fill out the following:

## What steps do I need to do when I download this repo to get it running?

Make sure you have a working `pipenv` install beforehand!

On macOS: `brew install pipenv`

On Linux: get it from your package manager

On Windows: `¯\_(ツ)_/¯`

Once you have ensured that `pipenv` worked, install all dependencies
with `pipenv install`, then move to the section below.

## What commands starts the server?

For the development server: `pipenv run flask --app server.py run`

For the production server: `pipenv run gunicorn server:app`

## Before render

Before render you will need to set up a more production-grade backend server process. We will do this together in lecture, once that's done you should update the command above for starting the server to be the **production grade** server.