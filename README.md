# hacbs probe payload

This repo is forked from https://github.com/devfile-samples/devfile-sample-go-basic

The interesting bit is in the `.github/` directory where there is a github action that pushes a new
commit to the `build-happy-path` branch on a cron basis.

The purpose is to provide a regularly-updating repo which will trigger builds of this project in
HACBS. We measure the success rate and duration of those HACBS pipeline runs to give us an
indication of the health of the system.

See https://issues.redhat.com/browse/HACBS-150