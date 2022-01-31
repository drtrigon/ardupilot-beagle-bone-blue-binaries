***

**Pull Request https://github.com/ArduPilot/ardupilot/pull/19693 implements building of BeagleBoneBlue binaries into ArduPilot firmware and custom build server - therefore THIS GITHUB ACTION IS NOT NEEDED ANYMORE and will be disabled!**

**This repository will stay as a reference if anybody becomes interessted in how the build process works or needs to setup this as an action, e.g. for developping on a fork of ArduPilot.**

**How to use this repo:**
1. **create a fork**
2. **activate the github action on your fork**
***

# ardupilot-beagle-bone-blue-binaries

![workflow status](https://github.com/drtrigon/ardupilot-beagle-bone-blue-binaries/actions/workflows/ardupilot-beagle-bone-blue-binaries.yml/badge.svg)

Build the [ArduPilot](https://github.com/ArduPilot/ardupilot) binaries for the target [Beagle Bone Blue](https://ardupilot.org/copter/docs/common-beagle-bone-blue.html) as it currently is missing on https://firmware.ardupilot.org/ and https://custom.ardupilot.org/.

**Check the latest/topmost entry on https://github.com/drtrigon/ardupilot-beagle-bone-blue-binaries/actions and download the artifacts at the bottom of the page.**

Currently the target gets built once a day.

The workflow setup in this repo can be used in order to automate building of forked code in a simple and easy manner and by that enabling all colaborators on the fork to use the same binaries. (e.g. the container: `ardupilot/ardupilot-dev-base:latest` does not work on forks)

For more info refer to: https://github.com/ArduPilot/ardupilot/issues/18921, https://github.com/ArduPilot/ardupilot/pull/19600
