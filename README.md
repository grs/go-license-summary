# go-license-summary
simple script to collect license info for vendored packages in a go project

Pass in output from retrodep or similar and optional path to vendor
directory (else will assume it is in current directory).

Requires https://github.com/google/licenseclassifier on the path.

Will generate licenses/xml with summary information and licenses.tgz
containing the actual licenses.