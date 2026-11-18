# Gaussian Frame Hold for OBS Studio

OBS filter that holds frames per region. Whole-screen mode picks one rate from 120, 60, 40, 30, 24, 20 or 15 fps. Gaussian mode keeps the centre (about 5% of the frame area) at 120 fps and drops the outer edges to 15 fps.

Built on the layout of exeldro/obs-freeze-filter (GPL-2.0). Untested until the first CI build and an OBS run on the owner's PC.

## Build (GitHub Actions)
Push to master; the workflow in `.github/workflows/build.yml` builds Windows and macOS packages.
