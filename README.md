# B08H51JHS1-5.5

# 実行結果

```bash
$ circleci local execute 
Docker image digest: sha256:2c2fd6a4655b259ac40f3c168b82200d4a7cebdc8287c4eb866a348b0191403d
====>> Spin Up Environment
Build-agent version  ()
Docker Engine Version: 20.10.1
Kernel Version: Linux b2f626d8c1c2 5.4.0-1035-aws #37-Ubuntu SMP Wed Jan 6 21:01:57 UTC 2021 x86_64 Linux
Starting container cimg/node:lts
  image is cached as cimg/node:lts, but refreshing...
lts: Pulling from cimg/node
Digest: sha256:f6ab0eb78b007434b722a3a5b9345010d5a4a0ec5a7aa4acf802aa2d88fb0090
Status: Image is up to date for cimg/node:lts
  using image cimg/node@sha256:f6ab0eb78b007434b722a3a5b9345010d5a4a0ec5a7aa4acf802aa2d88fb0090
====>> Preparing Environment Variables
Using build environment variables:
  BASH_ENV=/tmp/.bash_env-localbuild-1611990307
  CI=true
  CIRCLECI=true
  CIRCLE_BRANCH=main
  CIRCLE_BUILD_NUM=
  CIRCLE_JOB=build
  CIRCLE_NODE_INDEX=0
  CIRCLE_NODE_TOTAL=1
  CIRCLE_REPOSITORY_URL=git@github.com:ys-office/B08H51JHS1-5.5.git
  CIRCLE_SHA1=38464e2088a1fc64c3455e420b185621d2961176
  CIRCLE_SHELL_ENV=/tmp/.bash_env-localbuild-1611990307
  CIRCLE_WORKING_DIRECTORY=~/project


The redacted variables listed above will be masked in run step output.====>> ビルトイン環境変数の利用
  #!/bin/bash -eo pipefail
echo "CI is '${CI}'"
echo "CIRCLE_SHA1 is '${CIRCLE_SHA1}'"
echo "CIRCLE_BRANCH is '${CIRCLE_BRANCH}'"

CI is 'true'
CIRCLE_SHA1 is '38464e2088a1fc64c3455e420b185621d2961176'
CIRCLE_BRA
```
