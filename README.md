# Seed Tags
A base set of musical tags, for use across multiple projects

We currently deal with 3 sets of tags: [Instruments](instruments.yml), [Genres](genres.yml) and [Moods](moods.yml).

We've collated the tags from a number of locations and cleaned them up to create a single point of reference.

Each set of tags are represented as YAML hashes. The key for each item is a "sluggified" version of the name, useful for de-duplication etc. The value is the readable/humanised label for the tag.

You can include this repository as a submodule for use in your projects.
