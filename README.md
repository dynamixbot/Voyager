# Voyager - a magic scratch indexer
Voyager is a drop in replacement to ScratchDB. It indexes the Scratch Forums and makes this data accessible via a REST API.

## Canary Release Channel
This branch is dedicated to releasing experimental builds of Voyager. This is the most actively updated and changing build of Voyager, as well as being the most unstable. This is the only branch to which pull requests can be merged. Versions are immediately deprecated once a newer one comes out. No warranty is granted and no liability is taken for using Canary, as part of other license terms as per GNU AGPL 3.0.

### How to use Voyager Canary

Each Voyager build utilizes the same core architecture of Pioneer and Horizons, out of which Horizons is the one actively accessed by your application. The same REST API exists for Canary, except Canary uses a different root directory under '/canary' to use it, unlike the Beta and Stable versions using '/beta' and '/stable'. Horizons Canary does not have the same indexed data as Beta and Stable, so expect inconsistencies and non-reliant access, as Canary is not meant to serve as a permanent replacement for ScratchDB.
