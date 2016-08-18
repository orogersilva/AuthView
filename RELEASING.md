Release Process
===============

Release
-------

1. Update the version on `app/build.gradle`, in case of some relevant update would have been occurred,
    such as internal (and/or public) changes.

2. Update the `CHANGELOG.md` describing the internal (and/or public) changes.

3. Commit the changes with `git commit -am "Preparing version X.Y.Z"`, changing `X.Y.Z` with the
    version number.

4. Crie uma tag anotada com `git tag -a X.Y.Z -m "Versão X.Y.Z"`, substituindo 'X.Y.Z' com o número
    da nova versão.

4. Create a annotated tag with `git tag -a X.Y.Z -m "Version X.Y.Z"`, changing `X.Y.Z` with the
    version number.

5. Push (`git push`) and push tag (`git push --tags`).

6. :shipit: