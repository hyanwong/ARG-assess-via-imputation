# ARG-assess-via-imputation

See https://github.com/tskit-dev/tsinfer/issues/652 for justification.

However, this repo should not be tsinfer specific. We want to be able to judge any ARG inference algorithm via its accuracy in imputation.

Note that there are 2 sorts of imputation we could do

1. missing site imputation (mark all samples as having missing data at particular sites)
2. scattered sample imputation (mark some samples as having missing data at many sites)
