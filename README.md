# Roslyn Offline Packaging

This is a new iteration for Roslyn offline packaging. To initialize the offline package, follow these steps:

1. Clone this repository
2. Fetch the submodules by running `git submodule update --init`
3. Run initializeoffline.sh

To build Roslyn offline, use `./build.sh --restore --build --configuration Release-MONO /p:DisableNerdbankVersioning=true` from the roslyn directory.
