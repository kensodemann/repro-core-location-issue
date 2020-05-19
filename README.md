# repro-core-location-issue
Repro issue with CoreLocation not being found during build.

1. clone
1. npm i
1. npm run build
1. npx cap update
1. npx cap open ios

Try to build and you will get an error about ÇoreLocation missing. The `cordova-plugin-marketingcloudsdk` relies on it
and it apparently is not being brought in properly.
