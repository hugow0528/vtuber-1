
2026-04-12T12:32:14.6676924Z Current runner version: '2.333.1'
2026-04-12T12:32:14.6701752Z ##[group]Runner Image Provisioner
2026-04-12T12:32:14.6702600Z Hosted Compute Agent
2026-04-12T12:32:14.6703664Z Version: 20260213.493
2026-04-12T12:32:14.6704323Z Commit: 5c115507f6dd24b8de37d8bbe0bb4509d0cc0fa3
2026-04-12T12:32:14.6705062Z Build Date: 2026-02-13T00:28:41Z
2026-04-12T12:32:14.6705787Z Worker ID: {96282386-255b-4ee9-a286-767f4a5973f0}
2026-04-12T12:32:14.6706496Z Azure Region: eastus
2026-04-12T12:32:14.6707007Z ##[endgroup]
2026-04-12T12:32:14.6708505Z ##[group]Operating System
2026-04-12T12:32:14.6709134Z Ubuntu
2026-04-12T12:32:14.6709639Z 24.04.4
2026-04-12T12:32:14.6710516Z LTS
2026-04-12T12:32:14.6711046Z ##[endgroup]
2026-04-12T12:32:14.6711567Z ##[group]Runner Image
2026-04-12T12:32:14.6712257Z Image: ubuntu-24.04
2026-04-12T12:32:14.6712770Z Version: 20260406.80.1
2026-04-12T12:32:14.6714300Z Included Software: https://github.com/actions/runner-images/blob/ubuntu24/20260406.80/images/ubuntu/Ubuntu2404-Readme.md
2026-04-12T12:32:14.6715738Z Image Release: https://github.com/actions/runner-images/releases/tag/ubuntu24%2F20260406.80
2026-04-12T12:32:14.6716742Z ##[endgroup]
2026-04-12T12:32:14.6717808Z ##[group]GITHUB_TOKEN Permissions
2026-04-12T12:32:14.6720171Z Contents: write
2026-04-12T12:32:14.6720792Z Metadata: read
2026-04-12T12:32:14.6721346Z ##[endgroup]
2026-04-12T12:32:14.6725107Z Secret source: Actions
2026-04-12T12:32:14.6725831Z Prepare workflow directory
2026-04-12T12:32:14.7047738Z Prepare all required actions
2026-04-12T12:32:14.7084087Z Getting action download info
2026-04-12T12:32:14.9238413Z Download action repository 'actions/checkout@v4' (SHA:34e114876b0b11c390a56381ad16ebd13914f8d5)
2026-04-12T12:32:15.0618444Z Download action repository 'actions/setup-python@v5' (SHA:a26af69be951a213d495a4c3e4e4022e16d87065)
2026-04-12T12:32:15.2913515Z Complete job name: Generate Short & Upload to YouTube
2026-04-12T12:32:15.3602137Z ##[group]Run actions/checkout@v4
2026-04-12T12:32:15.3602936Z with:
2026-04-12T12:32:15.3603910Z   repository: kychugo/vtuber-1
2026-04-12T12:32:15.3604578Z   token: ***
2026-04-12T12:32:15.3604989Z   ssh-strict: true
2026-04-12T12:32:15.3605406Z   ssh-user: git
2026-04-12T12:32:15.3605815Z   persist-credentials: true
2026-04-12T12:32:15.3606283Z   clean: true
2026-04-12T12:32:15.3606705Z   sparse-checkout-cone-mode: true
2026-04-12T12:32:15.3607197Z   fetch-depth: 1
2026-04-12T12:32:15.3607592Z   fetch-tags: false
2026-04-12T12:32:15.3608005Z   show-progress: true
2026-04-12T12:32:15.3608420Z   lfs: false
2026-04-12T12:32:15.3608793Z   submodules: false
2026-04-12T12:32:15.3609212Z   set-safe-directory: true
2026-04-12T12:32:15.3609960Z ##[endgroup]
2026-04-12T12:32:15.4679013Z Syncing repository: kychugo/vtuber-1
2026-04-12T12:32:15.4680715Z ##[group]Getting Git version info
2026-04-12T12:32:15.4681580Z Working directory is '/home/runner/work/vtuber-1/vtuber-1'
2026-04-12T12:32:15.4682621Z [command]/usr/bin/git version
2026-04-12T12:32:15.4717092Z git version 2.53.0
2026-04-12T12:32:15.4741290Z ##[endgroup]
2026-04-12T12:32:15.4755310Z Temporarily overriding HOME='/home/runner/work/_temp/0f234b83-e24f-444e-b54e-03f112df4135' before making global git config changes
2026-04-12T12:32:15.4768283Z Adding repository directory to the temporary git global config as a safe directory
2026-04-12T12:32:15.4769550Z [command]/usr/bin/git config --global --add safe.directory /home/runner/work/vtuber-1/vtuber-1
2026-04-12T12:32:15.4800665Z Deleting the contents of '/home/runner/work/vtuber-1/vtuber-1'
2026-04-12T12:32:15.4804309Z ##[group]Initializing the repository
2026-04-12T12:32:15.4808545Z [command]/usr/bin/git init /home/runner/work/vtuber-1/vtuber-1
2026-04-12T12:32:15.4879475Z hint: Using 'master' as the name for the initial branch. This default branch name
2026-04-12T12:32:15.4880953Z hint: will change to "main" in Git 3.0. To configure the initial branch name
2026-04-12T12:32:15.4882414Z hint: to use in all of your new repositories, which will suppress this warning,
2026-04-12T12:32:15.4883824Z hint: call:
2026-04-12T12:32:15.4884752Z hint:
2026-04-12T12:32:15.4885483Z hint: 	git config --global init.defaultBranch <name>
2026-04-12T12:32:15.4886417Z hint:
2026-04-12T12:32:15.4887337Z hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
2026-04-12T12:32:15.4888772Z hint: 'development'. The just-created branch can be renamed via this command:
2026-04-12T12:32:15.4889869Z hint:
2026-04-12T12:32:15.4890482Z hint: 	git branch -m <name>
2026-04-12T12:32:15.4891185Z hint:
2026-04-12T12:32:15.4892130Z hint: Disable this message with "git config set advice.defaultBranchName false"
2026-04-12T12:32:15.4893898Z Initialized empty Git repository in /home/runner/work/vtuber-1/vtuber-1/.git/
2026-04-12T12:32:15.4896293Z [command]/usr/bin/git remote add origin https://github.com/kychugo/vtuber-1
2026-04-12T12:32:15.4925126Z ##[endgroup]
2026-04-12T12:32:15.4926270Z ##[group]Disabling automatic garbage collection
2026-04-12T12:32:15.4929989Z [command]/usr/bin/git config --local gc.auto 0
2026-04-12T12:32:15.4959691Z ##[endgroup]
2026-04-12T12:32:15.4960747Z ##[group]Setting up auth
2026-04-12T12:32:15.4967337Z [command]/usr/bin/git config --local --name-only --get-regexp core\.sshCommand
2026-04-12T12:32:15.4999213Z [command]/usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'core\.sshCommand' && git config --local --unset-all 'core.sshCommand' || :"
2026-04-12T12:32:15.5284341Z [command]/usr/bin/git config --local --name-only --get-regexp http\.https\:\/\/github\.com\/\.extraheader
2026-04-12T12:32:15.5315486Z [command]/usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'http\.https\:\/\/github\.com\/\.extraheader' && git config --local --unset-all 'http.https://github.com/.extraheader' || :"
2026-04-12T12:32:15.5542341Z [command]/usr/bin/git config --local --name-only --get-regexp ^includeIf\.gitdir:
2026-04-12T12:32:15.5583717Z [command]/usr/bin/git submodule foreach --recursive git config --local --show-origin --name-only --get-regexp remote.origin.url
2026-04-12T12:32:15.5816169Z [command]/usr/bin/git config --local http.https://github.com/.extraheader AUTHORIZATION: basic ***
2026-04-12T12:32:15.5850717Z ##[endgroup]
2026-04-12T12:32:15.5851811Z ##[group]Fetching the repository
2026-04-12T12:32:15.5859976Z [command]/usr/bin/git -c protocol.version=2 fetch --no-tags --prune --no-recurse-submodules --depth=1 origin +aeec00e5d6b873cdeba65dc3f4098b4ae5251d03:refs/remotes/origin/main
2026-04-12T12:32:17.5209941Z From https://github.com/kychugo/vtuber-1
2026-04-12T12:32:17.5211151Z  * [new ref]         aeec00e5d6b873cdeba65dc3f4098b4ae5251d03 -> origin/main
2026-04-12T12:32:17.5238294Z ##[endgroup]
2026-04-12T12:32:17.5239742Z ##[group]Determining the checkout info
2026-04-12T12:32:17.5241410Z ##[endgroup]
2026-04-12T12:32:17.5246749Z [command]/usr/bin/git sparse-checkout disable
2026-04-12T12:32:17.5285481Z [command]/usr/bin/git config --local --unset-all extensions.worktreeConfig
2026-04-12T12:32:17.5312565Z ##[group]Checking out the ref
2026-04-12T12:32:17.5316958Z [command]/usr/bin/git checkout --progress --force -B main refs/remotes/origin/main
2026-04-12T12:32:17.6438644Z Switched to a new branch 'main'
2026-04-12T12:32:17.6439890Z branch 'main' set up to track 'origin/main'.
2026-04-12T12:32:17.6446839Z ##[endgroup]
2026-04-12T12:32:17.6485997Z [command]/usr/bin/git log -1 --format=%H
2026-04-12T12:32:17.6508508Z aeec00e5d6b873cdeba65dc3f4098b4ae5251d03
2026-04-12T12:32:17.6708339Z ##[group]Run sudo apt-get update -qq
2026-04-12T12:32:17.6709068Z [36;1msudo apt-get update -qq[0m
2026-04-12T12:32:17.6709769Z [36;1msudo apt-get install -y fonts-liberation fonts-noto[0m
2026-04-12T12:32:17.6735764Z shell: /usr/bin/bash -e {0}
2026-04-12T12:32:17.6736322Z ##[endgroup]
2026-04-12T12:32:29.4956503Z Reading package lists...
2026-04-12T12:32:29.6758768Z Building dependency tree...
2026-04-12T12:32:29.6766022Z Reading state information...
2026-04-12T12:32:29.8362453Z fonts-liberation is already the newest version (1:2.1.5-3).
2026-04-12T12:32:29.8364044Z fonts-liberation set to manually installed.
2026-04-12T12:32:29.8364475Z The following additional packages will be installed:
2026-04-12T12:32:29.8364982Z   fonts-noto-cjk fonts-noto-cjk-extra fonts-noto-core fonts-noto-extra
2026-04-12T12:32:29.8368713Z   fonts-noto-mono fonts-noto-ui-core fonts-noto-ui-extra fonts-noto-unhinted
2026-04-12T12:32:29.8787928Z The following NEW packages will be installed:
2026-04-12T12:32:29.8788727Z   fonts-noto fonts-noto-cjk fonts-noto-cjk-extra fonts-noto-core
2026-04-12T12:32:29.8789349Z   fonts-noto-extra fonts-noto-mono fonts-noto-ui-core fonts-noto-ui-extra
2026-04-12T12:32:29.8793619Z   fonts-noto-unhinted
2026-04-12T12:32:29.8975523Z 0 upgraded, 9 newly installed, 0 to remove and 26 not upgraded.
2026-04-12T12:32:29.8976238Z Need to get 315 MB of archives.
2026-04-12T12:32:29.8976776Z After this operation, 779 MB of additional disk space will be used.
2026-04-12T12:32:29.8977338Z Get:1 file:/etc/apt/apt-mirrors.txt Mirrorlist [144 B]
2026-04-12T12:32:29.9246124Z Get:2 http://azure.archive.ubuntu.com/ubuntu noble/main amd64 fonts-noto-mono all 20201225-2 [435 kB]
2026-04-12T12:32:29.9371948Z Get:3 http://azure.archive.ubuntu.com/ubuntu noble/main amd64 fonts-noto-core all 20201225-2 [13.3 MB]
2026-04-12T12:32:30.1421141Z Get:4 http://azure.archive.ubuntu.com/ubuntu noble/universe amd64 fonts-noto all 20201225-2 [16.9 kB]
2026-04-12T12:32:30.1504188Z Get:5 http://azure.archive.ubuntu.com/ubuntu noble/main amd64 fonts-noto-cjk all 1:20230817+repack1-3 [61.2 MB]
2026-04-12T12:32:30.8976727Z Get:6 http://azure.archive.ubuntu.com/ubuntu noble/main amd64 fonts-noto-cjk-extra all 1:20230817+repack1-3 [145 MB]
2026-04-12T12:32:33.2440649Z Get:7 http://azure.archive.ubuntu.com/ubuntu noble/universe amd64 fonts-noto-extra all 20201225-2 [78.5 MB]
2026-04-12T12:32:34.0096094Z Get:8 http://azure.archive.ubuntu.com/ubuntu noble/main amd64 fonts-noto-ui-core all 20201225-2 [1552 kB]
2026-04-12T12:32:34.0334212Z Get:9 http://azure.archive.ubuntu.com/ubuntu noble/universe amd64 fonts-noto-ui-extra all 20201225-2 [15.5 MB]
2026-04-12T12:32:34.1900257Z Get:10 http://azure.archive.ubuntu.com/ubuntu noble/universe amd64 fonts-noto-unhinted all 20201225-2 [17.0 kB]
2026-04-12T12:32:34.4527782Z Fetched 315 MB in 4s (73.3 MB/s)
2026-04-12T12:32:34.4845422Z Selecting previously unselected package fonts-noto-mono.
2026-04-12T12:32:34.5862402Z (Reading database ... 
2026-04-12T12:32:34.5862871Z (Reading database ... 5%
2026-04-12T12:32:34.5863861Z (Reading database ... 10%
2026-04-12T12:32:34.5864177Z (Reading database ... 15%
2026-04-12T12:32:34.5864452Z (Reading database ... 20%
2026-04-12T12:32:34.5864767Z (Reading database ... 25%
2026-04-12T12:32:34.5865049Z (Reading database ... 30%
2026-04-12T12:32:34.5865334Z (Reading database ... 35%
2026-04-12T12:32:34.5865767Z (Reading database ... 40%
2026-04-12T12:32:34.5866477Z (Reading database ... 45%
2026-04-12T12:32:34.5866874Z (Reading database ... 50%
2026-04-12T12:32:34.6740324Z (Reading database ... 55%
2026-04-12T12:32:34.9260151Z (Reading database ... 60%
2026-04-12T12:32:35.1787016Z (Reading database ... 65%
2026-04-12T12:32:35.5084063Z (Reading database ... 70%
2026-04-12T12:32:35.7940511Z (Reading database ... 75%
2026-04-12T12:32:36.2075046Z (Reading database ... 80%
2026-04-12T12:32:36.7688108Z (Reading database ... 85%
2026-04-12T12:32:37.3501161Z (Reading database ... 90%
2026-04-12T12:32:37.9495661Z (Reading database ... 95%
2026-04-12T12:32:37.9496612Z (Reading database ... 100%
2026-04-12T12:32:37.9497202Z (Reading database ... 220613 files and directories currently installed.)
2026-04-12T12:32:37.9549554Z Preparing to unpack .../0-fonts-noto-mono_20201225-2_all.deb ...
2026-04-12T12:32:37.9574779Z Unpacking fonts-noto-mono (20201225-2) ...
2026-04-12T12:32:38.0057101Z Selecting previously unselected package fonts-noto-core.
2026-04-12T12:32:38.0199117Z Preparing to unpack .../1-fonts-noto-core_20201225-2_all.deb ...
2026-04-12T12:32:38.0208143Z Unpacking fonts-noto-core (20201225-2) ...
2026-04-12T12:32:38.2256643Z Selecting previously unselected package fonts-noto.
2026-04-12T12:32:38.2401671Z Preparing to unpack .../2-fonts-noto_20201225-2_all.deb ...
2026-04-12T12:32:38.2412277Z Unpacking fonts-noto (20201225-2) ...
2026-04-12T12:32:38.2631853Z Selecting previously unselected package fonts-noto-cjk.
2026-04-12T12:32:38.2792903Z Preparing to unpack .../3-fonts-noto-cjk_1%3a20230817+repack1-3_all.deb ...
2026-04-12T12:32:38.2905279Z Unpacking fonts-noto-cjk (1:20230817+repack1-3) ...
2026-04-12T12:32:38.7012843Z Selecting previously unselected package fonts-noto-cjk-extra.
2026-04-12T12:32:38.7158418Z Preparing to unpack .../4-fonts-noto-cjk-extra_1%3a20230817+repack1-3_all.deb ...
2026-04-12T12:32:38.7166717Z Unpacking fonts-noto-cjk-extra (1:20230817+repack1-3) ...
2026-04-12T12:32:39.6713554Z Selecting previously unselected package fonts-noto-extra.
2026-04-12T12:32:39.6875851Z Preparing to unpack .../5-fonts-noto-extra_20201225-2_all.deb ...
2026-04-12T12:32:39.6884646Z Unpacking fonts-noto-extra (20201225-2) ...
2026-04-12T12:32:40.9557398Z Selecting previously unselected package fonts-noto-ui-core.
2026-04-12T12:32:40.9708230Z Preparing to unpack .../6-fonts-noto-ui-core_20201225-2_all.deb ...
2026-04-12T12:32:40.9715367Z Unpacking fonts-noto-ui-core (20201225-2) ...
2026-04-12T12:32:41.0155410Z Selecting previously unselected package fonts-noto-ui-extra.
2026-04-12T12:32:41.0298846Z Preparing to unpack .../7-fonts-noto-ui-extra_20201225-2_all.deb ...
2026-04-12T12:32:41.0307199Z Unpacking fonts-noto-ui-extra (20201225-2) ...
2026-04-12T12:32:41.3439171Z Selecting previously unselected package fonts-noto-unhinted.
2026-04-12T12:32:41.3585787Z Preparing to unpack .../8-fonts-noto-unhinted_20201225-2_all.deb ...
2026-04-12T12:32:41.3593403Z Unpacking fonts-noto-unhinted (20201225-2) ...
2026-04-12T12:32:41.4054976Z Setting up fonts-noto-mono (20201225-2) ...
2026-04-12T12:32:41.4092369Z Setting up fonts-noto-ui-extra (20201225-2) ...
2026-04-12T12:32:41.4114024Z Setting up fonts-noto-extra (20201225-2) ...
2026-04-12T12:32:41.4135711Z Setting up fonts-noto-cjk (1:20230817+repack1-3) ...
2026-04-12T12:32:41.4202043Z Setting up fonts-noto-unhinted (20201225-2) ...
2026-04-12T12:32:41.4221843Z Setting up fonts-noto-ui-core (20201225-2) ...
2026-04-12T12:32:41.4242201Z Setting up fonts-noto-core (20201225-2) ...
2026-04-12T12:32:41.4270289Z Setting up fonts-noto-cjk-extra (1:20230817+repack1-3) ...
2026-04-12T12:32:41.4292067Z Setting up fonts-noto (20201225-2) ...
2026-04-12T12:32:41.4321116Z Processing triggers for fontconfig (2.15.0-1.1ubuntu2) ...
2026-04-12T12:32:43.0305953Z 
2026-04-12T12:32:43.0306575Z Running kernel seems to be up-to-date.
2026-04-12T12:32:43.0306937Z 
2026-04-12T12:32:43.0307070Z No services need to be restarted.
2026-04-12T12:32:43.0307560Z 
2026-04-12T12:32:43.0307695Z No containers need to be restarted.
2026-04-12T12:32:43.0307945Z 
2026-04-12T12:32:43.0308129Z No user sessions are running outdated binaries.
2026-04-12T12:32:43.0308436Z 
2026-04-12T12:32:43.0308734Z No VM guests are running outdated hypervisor (qemu) binaries on this host.
2026-04-12T12:32:43.9144514Z ##[group]Run ffmpeg -version | head -1
2026-04-12T12:32:43.9144861Z [36;1mffmpeg -version | head -1[0m
2026-04-12T12:32:43.9168115Z shell: /usr/bin/bash -e {0}
2026-04-12T12:32:43.9168357Z ##[endgroup]
2026-04-12T12:32:43.9214998Z /home/runner/work/_temp/42a627a9-05cb-418b-bdcb-8afa5d92aad3.sh: line 1: ffmpeg: command not found
2026-04-12T12:32:43.9374408Z ##[group]Run actions/setup-python@v5
2026-04-12T12:32:43.9374681Z with:
2026-04-12T12:32:43.9374868Z   python-version: 3.12
2026-04-12T12:32:43.9375079Z   cache: pip
2026-04-12T12:32:43.9375318Z   cache-dependency-path: scripts/requirements.txt
2026-04-12T12:32:43.9375629Z   check-latest: false
2026-04-12T12:32:43.9375957Z   token: ***
2026-04-12T12:32:43.9376159Z   update-environment: true
2026-04-12T12:32:43.9376405Z   allow-prereleases: false
2026-04-12T12:32:43.9376635Z   freethreaded: false
2026-04-12T12:32:43.9376842Z ##[endgroup]
2026-04-12T12:32:44.1022396Z ##[group]Installed versions
2026-04-12T12:32:44.1410849Z Successfully set up CPython (3.12.13)
2026-04-12T12:32:44.1411604Z ##[endgroup]
2026-04-12T12:32:44.1760450Z [command]/opt/hostedtoolcache/Python/3.12.13/x64/bin/pip cache dir
2026-04-12T12:32:45.5364457Z /home/runner/.cache/pip
2026-04-12T12:32:45.6443675Z pip cache is not found
2026-04-12T12:32:45.6551047Z ##[group]Run pip install -r scripts/requirements.txt
2026-04-12T12:32:45.6551439Z [36;1mpip install -r scripts/requirements.txt[0m
2026-04-12T12:32:45.6577408Z shell: /usr/bin/bash -e {0}
2026-04-12T12:32:45.6577663Z env:
2026-04-12T12:32:45.6577931Z   pythonLocation: /opt/hostedtoolcache/Python/3.12.13/x64
2026-04-12T12:32:45.6578397Z   PKG_CONFIG_PATH: /opt/hostedtoolcache/Python/3.12.13/x64/lib/pkgconfig
2026-04-12T12:32:45.6578823Z   Python_ROOT_DIR: /opt/hostedtoolcache/Python/3.12.13/x64
2026-04-12T12:32:45.6579198Z   Python2_ROOT_DIR: /opt/hostedtoolcache/Python/3.12.13/x64
2026-04-12T12:32:45.6579599Z   Python3_ROOT_DIR: /opt/hostedtoolcache/Python/3.12.13/x64
2026-04-12T12:32:45.6579978Z   LD_LIBRARY_PATH: /opt/hostedtoolcache/Python/3.12.13/x64/lib
2026-04-12T12:32:45.6580291Z ##[endgroup]
2026-04-12T12:32:47.0027306Z Collecting openai>=1.30.0 (from -r scripts/requirements.txt (line 1))
2026-04-12T12:32:47.0702823Z   Downloading openai-2.31.0-py3-none-any.whl.metadata (31 kB)
2026-04-12T12:32:47.0987332Z Collecting requests>=2.31.0 (from -r scripts/requirements.txt (line 2))
2026-04-12T12:32:47.1020874Z   Downloading requests-2.33.1-py3-none-any.whl.metadata (4.8 kB)
2026-04-12T12:32:47.1384532Z Collecting google-api-python-client>=2.130.0 (from -r scripts/requirements.txt (line 3))
2026-04-12T12:32:47.1418882Z   Downloading google_api_python_client-2.194.0-py3-none-any.whl.metadata (7.0 kB)
2026-04-12T12:32:47.1528110Z Collecting google-auth-httplib2>=0.2.0 (from -r scripts/requirements.txt (line 4))
2026-04-12T12:32:47.1566854Z   Downloading google_auth_httplib2-0.3.1-py3-none-any.whl.metadata (3.0 kB)
2026-04-12T12:32:47.1684221Z Collecting google-auth-oauthlib>=1.2.0 (from -r scripts/requirements.txt (line 5))
2026-04-12T12:32:47.1715385Z   Downloading google_auth_oauthlib-1.3.1-py3-none-any.whl.metadata (2.6 kB)
2026-04-12T12:32:47.1877291Z Collecting anyio<5,>=3.5.0 (from openai>=1.30.0->-r scripts/requirements.txt (line 1))
2026-04-12T12:32:47.1912558Z   Downloading anyio-4.13.0-py3-none-any.whl.metadata (4.5 kB)
2026-04-12T12:32:47.2020308Z Collecting distro<2,>=1.7.0 (from openai>=1.30.0->-r scripts/requirements.txt (line 1))
2026-04-12T12:32:47.2053713Z   Downloading distro-1.9.0-py3-none-any.whl.metadata (6.8 kB)
2026-04-12T12:32:47.2216858Z Collecting httpx<1,>=0.23.0 (from openai>=1.30.0->-r scripts/requirements.txt (line 1))
2026-04-12T12:32:47.2250412Z   Downloading httpx-0.28.1-py3-none-any.whl.metadata (7.1 kB)
2026-04-12T12:32:47.3067579Z Collecting jiter<1,>=0.10.0 (from openai>=1.30.0->-r scripts/requirements.txt (line 1))
2026-04-12T12:32:47.3112156Z   Downloading jiter-0.14.0-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (5.2 kB)
2026-04-12T12:32:47.4068488Z Collecting pydantic<3,>=1.9.0 (from openai>=1.30.0->-r scripts/requirements.txt (line 1))
2026-04-12T12:32:47.4105719Z   Downloading pydantic-2.12.5-py3-none-any.whl.metadata (90 kB)
2026-04-12T12:32:47.4255436Z Collecting sniffio (from openai>=1.30.0->-r scripts/requirements.txt (line 1))
2026-04-12T12:32:47.4291256Z   Downloading sniffio-1.3.1-py3-none-any.whl.metadata (3.9 kB)
2026-04-12T12:32:47.4574273Z Collecting tqdm>4 (from openai>=1.30.0->-r scripts/requirements.txt (line 1))
2026-04-12T12:32:47.4606218Z   Downloading tqdm-4.67.3-py3-none-any.whl.metadata (57 kB)
2026-04-12T12:32:47.4800100Z Collecting typing-extensions<5,>=4.11 (from openai>=1.30.0->-r scripts/requirements.txt (line 1))
2026-04-12T12:32:47.4834263Z   Downloading typing_extensions-4.15.0-py3-none-any.whl.metadata (3.3 kB)
2026-04-12T12:32:47.4980979Z Collecting idna>=2.8 (from anyio<5,>=3.5.0->openai>=1.30.0->-r scripts/requirements.txt (line 1))
2026-04-12T12:32:47.5014800Z   Downloading idna-3.11-py3-none-any.whl.metadata (8.4 kB)
2026-04-12T12:32:47.5205838Z Collecting certifi (from httpx<1,>=0.23.0->openai>=1.30.0->-r scripts/requirements.txt (line 1))
2026-04-12T12:32:47.5238240Z   Downloading certifi-2026.2.25-py3-none-any.whl.metadata (2.5 kB)
2026-04-12T12:32:47.5416436Z Collecting httpcore==1.* (from httpx<1,>=0.23.0->openai>=1.30.0->-r scripts/requirements.txt (line 1))
2026-04-12T12:32:47.5447911Z   Downloading httpcore-1.0.9-py3-none-any.whl.metadata (21 kB)
2026-04-12T12:32:47.5570148Z Collecting h11>=0.16 (from httpcore==1.*->httpx<1,>=0.23.0->openai>=1.30.0->-r scripts/requirements.txt (line 1))
2026-04-12T12:32:47.5602658Z   Downloading h11-0.16.0-py3-none-any.whl.metadata (8.3 kB)
2026-04-12T12:32:47.5715151Z Collecting annotated-types>=0.6.0 (from pydantic<3,>=1.9.0->openai>=1.30.0->-r scripts/requirements.txt (line 1))
2026-04-12T12:32:47.5755798Z   Downloading annotated_types-0.7.0-py3-none-any.whl.metadata (15 kB)
2026-04-12T12:32:48.1435985Z Collecting pydantic-core==2.41.5 (from pydantic<3,>=1.9.0->openai>=1.30.0->-r scripts/requirements.txt (line 1))
2026-04-12T12:32:48.1470592Z   Downloading pydantic_core-2.41.5-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (7.3 kB)
2026-04-12T12:32:48.1579869Z Collecting typing-inspection>=0.4.2 (from pydantic<3,>=1.9.0->openai>=1.30.0->-r scripts/requirements.txt (line 1))
2026-04-12T12:32:48.1613450Z   Downloading typing_inspection-0.4.2-py3-none-any.whl.metadata (2.6 kB)
2026-04-12T12:32:48.2444348Z Collecting charset_normalizer<4,>=2 (from requests>=2.31.0->-r scripts/requirements.txt (line 2))
2026-04-12T12:32:48.2480293Z   Downloading charset_normalizer-3.4.7-cp312-cp312-manylinux2014_x86_64.manylinux_2_17_x86_64.manylinux_2_28_x86_64.whl.metadata (40 kB)
2026-04-12T12:32:48.2712184Z Collecting urllib3<3,>=1.26 (from requests>=2.31.0->-r scripts/requirements.txt (line 2))
2026-04-12T12:32:48.2747202Z   Downloading urllib3-2.6.3-py3-none-any.whl.metadata (6.9 kB)
2026-04-12T12:32:48.2909343Z Collecting httplib2<1.0.0,>=0.19.0 (from google-api-python-client>=2.130.0->-r scripts/requirements.txt (line 3))
2026-04-12T12:32:48.2944508Z   Downloading httplib2-0.31.2-py3-none-any.whl.metadata (2.2 kB)
2026-04-12T12:32:48.3256298Z Collecting google-auth!=2.24.0,!=2.25.0,<3.0.0,>=1.32.0 (from google-api-python-client>=2.130.0->-r scripts/requirements.txt (line 3))
2026-04-12T12:32:48.3288564Z   Downloading google_auth-2.49.2-py3-none-any.whl.metadata (6.2 kB)
2026-04-12T12:32:48.3650523Z Collecting google-api-core!=2.0.*,!=2.1.*,!=2.2.*,!=2.3.0,<3.0.0,>=1.31.5 (from google-api-python-client>=2.130.0->-r scripts/requirements.txt (line 3))
2026-04-12T12:32:48.3687763Z   Downloading google_api_core-2.30.3-py3-none-any.whl.metadata (3.1 kB)
2026-04-12T12:32:48.3801461Z Collecting uritemplate<5,>=3.0.1 (from google-api-python-client>=2.130.0->-r scripts/requirements.txt (line 3))
2026-04-12T12:32:48.3834962Z   Downloading uritemplate-4.2.0-py3-none-any.whl.metadata (2.6 kB)
2026-04-12T12:32:48.3997074Z Collecting googleapis-common-protos<2.0.0,>=1.63.2 (from google-api-core!=2.0.*,!=2.1.*,!=2.2.*,!=2.3.0,<3.0.0,>=1.31.5->google-api-python-client>=2.130.0->-r scripts/requirements.txt (line 3))
2026-04-12T12:32:48.4030648Z   Downloading googleapis_common_protos-1.74.0-py3-none-any.whl.metadata (9.2 kB)
2026-04-12T12:32:48.5273415Z Collecting protobuf<8.0.0,>=4.25.8 (from google-api-core!=2.0.*,!=2.1.*,!=2.2.*,!=2.3.0,<3.0.0,>=1.31.5->google-api-python-client>=2.130.0->-r scripts/requirements.txt (line 3))
2026-04-12T12:32:48.5316977Z   Downloading protobuf-7.34.1-cp310-abi3-manylinux2014_x86_64.whl.metadata (595 bytes)
2026-04-12T12:32:48.5472467Z Collecting proto-plus<2.0.0,>=1.22.3 (from google-api-core!=2.0.*,!=2.1.*,!=2.2.*,!=2.3.0,<3.0.0,>=1.31.5->google-api-python-client>=2.130.0->-r scripts/requirements.txt (line 3))
2026-04-12T12:32:48.5506677Z   Downloading proto_plus-1.27.2-py3-none-any.whl.metadata (2.2 kB)
2026-04-12T12:32:48.5754485Z Collecting pyasn1-modules>=0.2.1 (from google-auth!=2.24.0,!=2.25.0,<3.0.0,>=1.32.0->google-api-python-client>=2.130.0->-r scripts/requirements.txt (line 3))
2026-04-12T12:32:48.5787046Z   Downloading pyasn1_modules-0.4.2-py3-none-any.whl.metadata (3.5 kB)
2026-04-12T12:32:48.7746372Z Collecting cryptography>=38.0.3 (from google-auth!=2.24.0,!=2.25.0,<3.0.0,>=1.32.0->google-api-python-client>=2.130.0->-r scripts/requirements.txt (line 3))
2026-04-12T12:32:48.7781704Z   Downloading cryptography-46.0.7-cp311-abi3-manylinux_2_34_x86_64.whl.metadata (5.7 kB)
2026-04-12T12:32:48.8024624Z Collecting pyparsing<4,>=3.1 (from httplib2<1.0.0,>=0.19.0->google-api-python-client>=2.130.0->-r scripts/requirements.txt (line 3))
2026-04-12T12:32:48.8055143Z   Downloading pyparsing-3.3.2-py3-none-any.whl.metadata (5.8 kB)
2026-04-12T12:32:48.8242461Z Collecting requests-oauthlib>=0.7.0 (from google-auth-oauthlib>=1.2.0->-r scripts/requirements.txt (line 5))
2026-04-12T12:32:48.8278578Z   Downloading requests_oauthlib-2.0.0-py2.py3-none-any.whl.metadata (11 kB)
2026-04-12T12:32:48.9131159Z Collecting cffi>=2.0.0 (from cryptography>=38.0.3->google-auth!=2.24.0,!=2.25.0,<3.0.0,>=1.32.0->google-api-python-client>=2.130.0->-r scripts/requirements.txt (line 3))
2026-04-12T12:32:48.9168919Z   Downloading cffi-2.0.0-cp312-cp312-manylinux2014_x86_64.manylinux_2_17_x86_64.whl.metadata (2.6 kB)
2026-04-12T12:32:48.9279032Z Collecting pycparser (from cffi>=2.0.0->cryptography>=38.0.3->google-auth!=2.24.0,!=2.25.0,<3.0.0,>=1.32.0->google-api-python-client>=2.130.0->-r scripts/requirements.txt (line 3))
2026-04-12T12:32:48.9313392Z   Downloading pycparser-3.0-py3-none-any.whl.metadata (8.2 kB)
2026-04-12T12:32:48.9505379Z Collecting pyasn1<0.7.0,>=0.6.1 (from pyasn1-modules>=0.2.1->google-auth!=2.24.0,!=2.25.0,<3.0.0,>=1.32.0->google-api-python-client>=2.130.0->-r scripts/requirements.txt (line 3))
2026-04-12T12:32:48.9538357Z   Downloading pyasn1-0.6.3-py3-none-any.whl.metadata (8.4 kB)
2026-04-12T12:32:48.9666010Z Collecting oauthlib>=3.0.0 (from requests-oauthlib>=0.7.0->google-auth-oauthlib>=1.2.0->-r scripts/requirements.txt (line 5))
2026-04-12T12:32:48.9699993Z   Downloading oauthlib-3.3.1-py3-none-any.whl.metadata (7.9 kB)
2026-04-12T12:32:48.9822094Z Downloading openai-2.31.0-py3-none-any.whl (1.2 MB)
2026-04-12T12:32:48.9967384Z    ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.2/1.2 MB 95.7 MB/s  0:00:00
2026-04-12T12:32:49.0002131Z Downloading anyio-4.13.0-py3-none-any.whl (114 kB)
2026-04-12T12:32:49.0055017Z Downloading distro-1.9.0-py3-none-any.whl (20 kB)
2026-04-12T12:32:49.0103560Z Downloading httpx-0.28.1-py3-none-any.whl (73 kB)
2026-04-12T12:32:49.0153868Z Downloading httpcore-1.0.9-py3-none-any.whl (78 kB)
2026-04-12T12:32:49.0205548Z Downloading jiter-0.14.0-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (353 kB)
2026-04-12T12:32:49.0262089Z Downloading pydantic-2.12.5-py3-none-any.whl (463 kB)
2026-04-12T12:32:49.0330749Z Downloading pydantic_core-2.41.5-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (2.1 MB)
2026-04-12T12:32:49.0427837Z    ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 2.1/2.1 MB 242.3 MB/s  0:00:00
2026-04-12T12:32:49.0468642Z Downloading typing_extensions-4.15.0-py3-none-any.whl (44 kB)
2026-04-12T12:32:49.0518419Z Downloading requests-2.33.1-py3-none-any.whl (64 kB)
2026-04-12T12:32:49.0569639Z Downloading charset_normalizer-3.4.7-cp312-cp312-manylinux2014_x86_64.manylinux_2_17_x86_64.manylinux_2_28_x86_64.whl (216 kB)
2026-04-12T12:32:49.0624020Z Downloading idna-3.11-py3-none-any.whl (71 kB)
2026-04-12T12:32:49.0673709Z Downloading urllib3-2.6.3-py3-none-any.whl (131 kB)
2026-04-12T12:32:49.0725000Z Downloading google_api_python_client-2.194.0-py3-none-any.whl (15.0 MB)
2026-04-12T12:32:49.1169293Z    ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 15.0/15.0 MB 350.6 MB/s  0:00:00
2026-04-12T12:32:49.1206317Z Downloading google_auth_httplib2-0.3.1-py3-none-any.whl (9.5 kB)
2026-04-12T12:32:49.1258338Z Downloading google_api_core-2.30.3-py3-none-any.whl (173 kB)
2026-04-12T12:32:49.1315381Z Downloading google_auth-2.49.2-py3-none-any.whl (240 kB)
2026-04-12T12:32:49.1371203Z Downloading googleapis_common_protos-1.74.0-py3-none-any.whl (300 kB)
2026-04-12T12:32:49.1426251Z Downloading httplib2-0.31.2-py3-none-any.whl (91 kB)
2026-04-12T12:32:49.1476735Z Downloading proto_plus-1.27.2-py3-none-any.whl (50 kB)
2026-04-12T12:32:49.1529541Z Downloading protobuf-7.34.1-cp310-abi3-manylinux2014_x86_64.whl (324 kB)
2026-04-12T12:32:49.1585441Z Downloading pyparsing-3.3.2-py3-none-any.whl (122 kB)
2026-04-12T12:32:49.1638000Z Downloading uritemplate-4.2.0-py3-none-any.whl (11 kB)
2026-04-12T12:32:49.1686577Z Downloading google_auth_oauthlib-1.3.1-py3-none-any.whl (19 kB)
2026-04-12T12:32:49.1738714Z Downloading annotated_types-0.7.0-py3-none-any.whl (13 kB)
2026-04-12T12:32:49.1787759Z Downloading certifi-2026.2.25-py3-none-any.whl (153 kB)
2026-04-12T12:32:49.1840587Z Downloading cryptography-46.0.7-cp311-abi3-manylinux_2_34_x86_64.whl (4.5 MB)
2026-04-12T12:32:49.1986815Z    ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 4.5/4.5 MB 348.5 MB/s  0:00:00
2026-04-12T12:32:49.2020692Z Downloading cffi-2.0.0-cp312-cp312-manylinux2014_x86_64.manylinux_2_17_x86_64.whl (219 kB)
2026-04-12T12:32:49.2074222Z Downloading h11-0.16.0-py3-none-any.whl (37 kB)
2026-04-12T12:32:49.2122472Z Downloading pyasn1_modules-0.4.2-py3-none-any.whl (181 kB)
2026-04-12T12:32:49.2174589Z Downloading pyasn1-0.6.3-py3-none-any.whl (83 kB)
2026-04-12T12:32:49.2227380Z Downloading requests_oauthlib-2.0.0-py2.py3-none-any.whl (24 kB)
2026-04-12T12:32:49.2275199Z Downloading oauthlib-3.3.1-py3-none-any.whl (160 kB)
2026-04-12T12:32:49.2325015Z Downloading tqdm-4.67.3-py3-none-any.whl (78 kB)
2026-04-12T12:32:49.2374118Z Downloading typing_inspection-0.4.2-py3-none-any.whl (14 kB)
2026-04-12T12:32:49.2423735Z Downloading pycparser-3.0-py3-none-any.whl (48 kB)
2026-04-12T12:32:49.2472098Z Downloading sniffio-1.3.1-py3-none-any.whl (10 kB)
2026-04-12T12:32:49.3755695Z Installing collected packages: urllib3, uritemplate, typing-extensions, tqdm, sniffio, pyparsing, pycparser, pyasn1, protobuf, oauthlib, jiter, idna, h11, distro, charset_normalizer, certifi, annotated-types, typing-inspection, requests, pydantic-core, pyasn1-modules, proto-plus, httplib2, httpcore, googleapis-common-protos, cffi, anyio, requests-oauthlib, pydantic, httpx, cryptography, openai, google-auth, google-auth-oauthlib, google-auth-httplib2, google-api-core, google-api-python-client
2026-04-12T12:32:52.6182456Z 
2026-04-12T12:32:52.6220241Z Successfully installed annotated-types-0.7.0 anyio-4.13.0 certifi-2026.2.25 cffi-2.0.0 charset_normalizer-3.4.7 cryptography-46.0.7 distro-1.9.0 google-api-core-2.30.3 google-api-python-client-2.194.0 google-auth-2.49.2 google-auth-httplib2-0.3.1 google-auth-oauthlib-1.3.1 googleapis-common-protos-1.74.0 h11-0.16.0 httpcore-1.0.9 httplib2-0.31.2 httpx-0.28.1 idna-3.11 jiter-0.14.0 oauthlib-3.3.1 openai-2.31.0 proto-plus-1.27.2 protobuf-7.34.1 pyasn1-0.6.3 pyasn1-modules-0.4.2 pycparser-3.0 pydantic-2.12.5 pydantic-core-2.41.5 pyparsing-3.3.2 requests-2.33.1 requests-oauthlib-2.0.0 sniffio-1.3.1 tqdm-4.67.3 typing-extensions-4.15.0 typing-inspection-0.4.2 uritemplate-4.2.0 urllib3-2.6.3
2026-04-12T12:32:53.0034831Z ##[group]Run python scripts/generate_short.py
2026-04-12T12:32:53.0035191Z [36;1mpython scripts/generate_short.py[0m
2026-04-12T12:32:53.0058478Z shell: /usr/bin/bash -e {0}
2026-04-12T12:32:53.0058722Z env:
2026-04-12T12:32:53.0058983Z   pythonLocation: /opt/hostedtoolcache/Python/3.12.13/x64
2026-04-12T12:32:53.0059396Z   PKG_CONFIG_PATH: /opt/hostedtoolcache/Python/3.12.13/x64/lib/pkgconfig
2026-04-12T12:32:53.0059802Z   Python_ROOT_DIR: /opt/hostedtoolcache/Python/3.12.13/x64
2026-04-12T12:32:53.0060168Z   Python2_ROOT_DIR: /opt/hostedtoolcache/Python/3.12.13/x64
2026-04-12T12:32:53.0060529Z   Python3_ROOT_DIR: /opt/hostedtoolcache/Python/3.12.13/x64
2026-04-12T12:32:53.0060887Z   LD_LIBRARY_PATH: /opt/hostedtoolcache/Python/3.12.13/x64/lib
2026-04-12T12:32:53.0061402Z   POLLINATIONS_API_KEY: ***
2026-04-12T12:32:53.0061863Z   YOUTUBE_CLIENT_ID: ***
2026-04-12T12:32:53.0062184Z   YOUTUBE_CLIENT_SECRET: ***
2026-04-12T12:32:53.0062591Z   YOUTUBE_REFRESH_TOKEN: 
2026-04-12T12:32:53.0062837Z   CUSTOM_TOPIC: 
2026-04-12T12:32:53.0063205Z ##[endgroup]
2026-04-12T12:33:36.5527877Z Traceback (most recent call last):
2026-04-12T12:33:36.5528755Z [1/5] Asking AI to generate content + SEO metadata …
2026-04-12T12:33:36.5539082Z   File "/home/runner/work/vtuber-1/vtuber-1/scripts/generate_short.py", line 667, in <module>
2026-04-12T12:33:36.5539593Z     Trying model: openai-large
2026-04-12T12:33:36.5539967Z     ✓ Model openai-large succeeded
2026-04-12T12:33:36.5540291Z     Title : Studio Ghibli AI Trend in 45 Seconds! #Shorts
2026-04-12T12:33:36.5540643Z [2/5] Generating AI background image …
2026-04-12T12:33:36.5540912Z     Trying image model: flux
2026-04-12T12:33:36.5541184Z     ✓ Image saved (126 KB) via flux
2026-04-12T12:33:36.5541445Z [3/5] Generating TTS audio …
2026-04-12T12:33:36.5541690Z     Trying TTS model: elevenlabs
2026-04-12T12:33:36.5541979Z     ✓ TTS saved (727 KB) via elevenlabs
2026-04-12T12:33:36.5542263Z     main()
2026-04-12T12:33:36.5542728Z   File "/home/runner/work/vtuber-1/vtuber-1/scripts/generate_short.py", line 628, in main
2026-04-12T12:33:36.5543447Z     speech_dur = get_audio_duration(audio_path)
2026-04-12T12:33:36.5543735Z                  ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
2026-04-12T12:33:36.5544239Z   File "/home/runner/work/vtuber-1/vtuber-1/scripts/generate_short.py", line 328, in get_audio_duration
2026-04-12T12:33:36.5544708Z     result = subprocess.run(
2026-04-12T12:33:36.5544934Z              ^^^^^^^^^^^^^^^
2026-04-12T12:33:36.5545362Z   File "/opt/hostedtoolcache/Python/3.12.13/x64/lib/python3.12/subprocess.py", line 548, in run
2026-04-12T12:33:36.5908267Z     with Popen(*popenargs, **kwargs) as process:
2026-04-12T12:33:36.5908794Z          ^^^^^^^^^^^^^^^^^^^^^^^^^^^
2026-04-12T12:33:36.5909684Z   File "/opt/hostedtoolcache/Python/3.12.13/x64/lib/python3.12/subprocess.py", line 1026, in __init__
2026-04-12T12:33:36.5911080Z     self._execute_child(args, executable, preexec_fn, close_fds,
2026-04-12T12:33:36.5912109Z   File "/opt/hostedtoolcache/Python/3.12.13/x64/lib/python3.12/subprocess.py", line 1955, in _execute_child
2026-04-12T12:33:36.5915559Z     raise child_exception_type(errno_num, err_msg, err_filename)
2026-04-12T12:33:36.5916207Z FileNotFoundError: [Errno 2] No such file or directory: 'ffprobe'
2026-04-12T12:33:36.7140142Z ##[error]Process completed with exit code 1.
2026-04-12T12:33:36.7188208Z ##[group]Run git config user.name "github-actions[bot]"
2026-04-12T12:33:36.7188626Z [36;1mgit config user.name "github-actions[bot]"[0m
2026-04-12T12:33:36.7189047Z [36;1mgit config user.email "github-actions[bot]@users.noreply.github.com"[0m
2026-04-12T12:33:36.7189465Z [36;1mgit add videos/ logs/ 2>/dev/null || true[0m
2026-04-12T12:33:36.7189774Z [36;1mif git diff --cached --quiet; then[0m
2026-04-12T12:33:36.7190051Z [36;1m  echo "Nothing new to commit."[0m
2026-04-12T12:33:36.7190302Z [36;1melse[0m
2026-04-12T12:33:36.7190626Z [36;1m  git commit -m "chore: auto-backup video and update upload log [skip ci]"[0m
2026-04-12T12:33:36.7191019Z [36;1m  git push[0m
2026-04-12T12:33:36.7191212Z [36;1mfi[0m
2026-04-12T12:33:36.7213909Z shell: /usr/bin/bash -e {0}
2026-04-12T12:33:36.7214138Z env:
2026-04-12T12:33:36.7214393Z   pythonLocation: /opt/hostedtoolcache/Python/3.12.13/x64
2026-04-12T12:33:36.7214852Z   PKG_CONFIG_PATH: /opt/hostedtoolcache/Python/3.12.13/x64/lib/pkgconfig
2026-04-12T12:33:36.7215254Z   Python_ROOT_DIR: /opt/hostedtoolcache/Python/3.12.13/x64
2026-04-12T12:33:36.7215616Z   Python2_ROOT_DIR: /opt/hostedtoolcache/Python/3.12.13/x64
2026-04-12T12:33:36.7215975Z   Python3_ROOT_DIR: /opt/hostedtoolcache/Python/3.12.13/x64
2026-04-12T12:33:36.7216347Z   LD_LIBRARY_PATH: /opt/hostedtoolcache/Python/3.12.13/x64/lib
2026-04-12T12:33:36.7216646Z ##[endgroup]
2026-04-12T12:33:36.7958630Z Nothing new to commit.
2026-04-12T12:33:36.8047795Z Post job cleanup.
2026-04-12T12:33:36.8993148Z [command]/usr/bin/git version
2026-04-12T12:33:36.9029860Z git version 2.53.0
2026-04-12T12:33:36.9069680Z Temporarily overriding HOME='/home/runner/work/_temp/b2b98069-1bf2-4564-8e1f-5b55b8616f82' before making global git config changes
2026-04-12T12:33:36.9070845Z Adding repository directory to the temporary git global config as a safe directory
2026-04-12T12:33:36.9082253Z [command]/usr/bin/git config --global --add safe.directory /home/runner/work/vtuber-1/vtuber-1
2026-04-12T12:33:36.9117250Z [command]/usr/bin/git config --local --name-only --get-regexp core\.sshCommand
2026-04-12T12:33:36.9168530Z [command]/usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'core\.sshCommand' && git config --local --unset-all 'core.sshCommand' || :"
2026-04-12T12:33:36.9389268Z [command]/usr/bin/git config --local --name-only --get-regexp http\.https\:\/\/github\.com\/\.extraheader
2026-04-12T12:33:36.9410684Z http.https://github.com/.extraheader
2026-04-12T12:33:36.9422971Z [command]/usr/bin/git config --local --unset-all http.https://github.com/.extraheader
2026-04-12T12:33:36.9453772Z [command]/usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'http\.https\:\/\/github\.com\/\.extraheader' && git config --local --unset-all 'http.https://github.com/.extraheader' || :"
2026-04-12T12:33:36.9695586Z [command]/usr/bin/git config --local --name-only --get-regexp ^includeIf\.gitdir:
2026-04-12T12:33:36.9730708Z [command]/usr/bin/git submodule foreach --recursive git config --local --show-origin --name-only --get-regexp remote.origin.url
2026-04-12T12:33:37.0103007Z Cleaning up orphan processes
2026-04-12T12:33:37.0392651Z ##[warning]Node.js 20 actions are deprecated. The following actions are running on Node.js 20 and may not work as expected: actions/checkout@v4, actions/setup-python@v5. Actions will be forced to run with Node.js 24 by default starting June 2nd, 2026. Node.js 20 will be removed from the runner on September 16th, 2026. Please check if updated versions of these actions are available that support Node.js 24. To opt into Node.js 24 now, set the FORCE_JAVASCRIPT_ACTIONS_TO_NODE24=true environment variable on the runner or in your workflow file. Once Node.js 24 becomes the default, you can temporarily opt out by setting ACTIONS_ALLOW_USE_UNSECURE_NODE_VERSION=true. For more information see: https://github.blog/changelog/2025-09-19-deprecation-of-node-20-on-github-actions-runners/


Now is bugged,also,it is now spending my token!add if error but for the thing that generated ,stor it and use for next time
