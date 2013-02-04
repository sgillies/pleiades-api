Pleiades Place API
==================

Home: http://api.pleiades.stoa.org

Discussion: https://groups.google.com/a/nyu.edu/group/pleiades-community-group

In collaboration with developers using Pleiades place data, we are developing
new HTTP + JSON services such as

* Site status (http://api.pleiades.stoa.org/#status)
* Place data (http://api.pleiades.stoa.org/#place)
* Search (coming soon)

Developers: please use this project's issue tracker
(https://github.com/isawnyu/pleiades-api/issues) to report problems or suggest
new features.

Example Application: Flickr
---------------------------

When a Flickr photo is given a Pleiades machine tag like
``pleiades:depicts=628932`` Flickr requests
http://pleiades.stoa.org/places/628932/json, extracts the title of that place
resource from the JSON response, and then writes it into a line of text under
the "Additional Info" section. See the phrase "Depicts the ancient site of
Argaeus Mons" on the page
https://secure.flickr.com/photos/erdalce/425604251/in/pool-pleiades-places.

