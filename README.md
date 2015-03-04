# fbrcrsi-addhostingpics
Add HostingPics service on phpBB 3.1.3 message editor 

## Quick Install
You can install this on the latest release of phpBB 3.1.3 by following the steps below:

1. [Download the latest release](https://github.com/fbrcrsi/fbrcrsi-addhostingpics).
2. Unzip the downloaded release, and go to the folder to `fbrcrsi-addhostingpics-master`.
3. copy directory named `fbrcrsi` in the `ext` directory of your phpBB board.
4. Navigate in the ACP to `Customise -> Manage extensions`.
5. Look for `Add Hostingpics service` under the Disabled Extensions list, and click its `Enable` link.


Remember to purge cache each time you edit the templates after the installation

## Uninstall

1. Navigate in the ACP to `Customise -> Extension Management -> Extensions`.
2. Look for `Add HostingPics service` under the Enabled Extensions list, and click its `Disable` link.
3. To permanently uninstall, click `Delete Data` and then delete the `/ext/fbrcrsi/addhostingpics` directory.
