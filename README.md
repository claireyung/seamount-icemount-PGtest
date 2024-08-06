# seamount-icemount-PGtest

For MOM6, modified from the seamount test case in MOM6-examples, to test initialisation and spurious currents in a simple, 2D set up.

The seamount case from MOM6-examples is modified to have a smaller minimum thickness, and a "roof" so that the icemount is symmetric with it. The icemount has a thickness presribed to get a symmetric geometry.


This branch is to test initialisation only.

Verified that PR  https://github.com/NOAA-GFDL/MOM6/commit/88d9eb79fc60ddd07269aa5fd641c9c101df9515 and  https://github.com/NOAA-GFDL/MOM6/commit/25989ad0b8e6cb3aeb52fe0bc387aefa352afe32 fix the initialisation of linear T and S under ice shelf.

MOM6 version used for testing is from dev/gfdl at commit https://github.com/NOAA-GFDL/MOM6/commit/f1ba822636bb937be1828a3e4f1e0e2155ea8b6a
