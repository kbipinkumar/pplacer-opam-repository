[pplacer](http://matsen.fhcrc.org/pplacer) dependencies not found in the main [OPAM repository](http://opam.ocamlpro.com/index.html)

# Adding packages

To add new packages / versions and deploy:

1. Checkout `master`
2. Add package definition to `packages`
3. Commit
4. Checkout the `gh-pages` branch
5. Merge `master` into `gh-pages`
6. Run `opam-admin make --generate-checksums <package_name>`
7. Commit
8. Push
