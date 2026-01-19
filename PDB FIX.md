

| Approach                                                                                                                              | Notes                                                                |
| ------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------- |
| 1. (This PR): Use `PathMap` to rewrite C:\BS\git to C:\git<br>e.g. `C:/git/wtg/GitHub/CargoWise/Common/Tools/ZRSGenerator/Program.cs` | This matches the developer builds, but it only works for default pat |
| 2. Use `ContinuousIntegrationBuild`<br>e.g. `/_/Common/Tools/ZRSGenerator/Program.cs`)                                                | This can fix the problem, but does not work out of the box. It requires add                                                                     |
| 3. Use symlink                                                                                                                        |                                                                      |