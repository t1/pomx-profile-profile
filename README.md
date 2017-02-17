## External Maven Profile for POMX Profiles

This is a [pomx](https://github.com/t1/pomx) profile for writing external profiles.

It is a profile, so it uses itself to build itself... now that's true recursion ;-)

The only magic is that `src/pomx.xml` symlinks to `pomx.xml`.

### Features

It mainly declares the `build-helper-maven-plugin` to attach `src/pomx.xml`.
