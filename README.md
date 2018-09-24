# secret-shield testing repo

this is to use with my [secret-shield refactor draft](https://github.com/agius/secret-shield-refactor-draft) for testing purposes

i don't like relying on an external repo for tests - running `npm test` should not require any network calls or have any OS side effects. it's an ugly hack

i was going to zip up this repo and include it in the `test/assets` folder of secret-shield, then unzip it in tests with Node's zlib functionality. but apparently that doesn't have great support for directories

adding a whole npm dependency (or several hundred, depending) or relying on potentially flakey OS tools like `tar` or `gunzip` seems like an even worse solution

so here we are ¯\\\_(ツ)_/¯
