PawnUnit is a testing tool for SourcePawn that can be embedded in SourceMod plugins.

**Feature summary:**
  * Easy to write tests. Complexity is hidden as far as SourcePawn allow so that the test code is clean.
  * Supports fully automated testing. No interaction is required by the user, unless the developer choose to make a console command for starting tests.
  * Embedded in plugin with minimal impact on plugin code. Nearly no need to modify existing plugin code other than including PawnUnit and starting it.

It's also prepared to support asynchronous tests, but because of limits in SourcePawn this can't be done in an elegant way yet.

**Source code**

The source is located in the pawnunit-dev repository, not the default repository.