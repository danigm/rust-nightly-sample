This is an example rust app that uses rust nightly to build the flatpak.

The rust-nightly is added as a source dependency that's installed in
/app/sdk/rust and you can use in the following sources to build your rust apps
or libs.

The rust binaries are removed at cleanup so the final flatpak bundle won't have
those files.
