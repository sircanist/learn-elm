
SUCCESS! Your project's dependencies and code have been upgraded.
However, your project may not yet compile due to API changes in your
dependencies.

See <https://github.com/elm/compiler/blob/master/upgrade-docs/0.19.md>
and the documentation for your dependencies for more information.

WARNING! 1 of your dependencies have not yet been upgraded to
support Elm 0.19.
  - https://github.com/elm-lang/websocket

Here are some common upgrade steps that you will need to do manually:

- elm/core
  - [ ] Replace uses of toString with String.fromInt, String.fromFloat, or Debug.toString as appropriate
- undefined
  - [ ] Read the new documentation here: https://package.elm-lang.org/packages/elm/time/latest/
  - [ ] Replace uses of Date and Time with Time.Posix
- elm/html
  - [ ] If you used Html.program*, install elm/browser and switch to Browser.element or Browser.docume
