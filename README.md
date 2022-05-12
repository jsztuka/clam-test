# clam-test
This repo is only for POC work.
Example output:
```
[clone-git-repo] Cloning into '/tekton/home/hacbs-test'...

[run-freshclam-at-first] /tekton/home/hacbs-test/.git/description: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/.git/hooks/applypatch-msg.sample: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/.git/hooks/commit-msg.sample: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/.git/hooks/post-update.sample: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/.git/hooks/pre-applypatch.sample: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/.git/hooks/pre-commit.sample: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/.git/hooks/pre-merge-commit.sample: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/.git/hooks/pre-push.sample: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/.git/hooks/pre-rebase.sample: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/.git/hooks/pre-receive.sample: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/.git/hooks/prepare-commit-msg.sample: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/.git/hooks/push-to-checkout.sample: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/.git/hooks/update.sample: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/.git/info/exclude: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/.git/refs/heads/main: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/.git/refs/remotes/origin/HEAD: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/.git/HEAD: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/.git/config: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/.git/objects/pack/pack-1dc3efecd75079a196b7f11556bf8b37fdc1ea7c.pack: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/.git/objects/pack/pack-1dc3efecd75079a196b7f11556bf8b37fdc1ea7c.idx: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/.git/packed-refs: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/.git/logs/refs/remotes/origin/HEAD: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/.git/logs/refs/heads/main: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/.git/logs/HEAD: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/.git/index: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/.github/workflows/README.md: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/.github/workflows/pr-checks.yaml: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/.github/workflows/release.yaml: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/.yamllint: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/Dockerfile: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/README.md: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/action.yml: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/policies/clair/vulnerabilities-check.rego: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/policies/image/deprecated-labels.rego: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/policies/image/inherited-labels.rego: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/policies/image/optional-labels.rego: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/policies/image/required-labels.rego: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/policies/repository/deprecated-image.rego: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/policies/rpm_manifest/unsigned-rpms.rego: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/test/conftest.sh: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/test/entrypoint.sh: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/unittests/test_clair/vulnerabilities-check_test.rego: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/unittests/test_data/clair.json: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/unittests/test_data/image.json: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/unittests/test_data/repository.json: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/unittests/test_data/rpm_manifest.json: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/unittests/test_images/deprecated-labels_test.rego: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/unittests/test_images/inherited-labels_test.rego: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/unittests/test_images/optional-labels_test.rego: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/unittests/test_images/required-labels_test.rego: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/unittests/test_repository/deprecated-image_test.rego: OK
[run-freshclam-at-first] /tekton/home/hacbs-test/unittests/test_rpm_manifest/unsigned-rpm_test.rego: OK
[run-freshclam-at-first] 
[run-freshclam-at-first] ----------- SCAN SUMMARY -----------
[run-freshclam-at-first] Known viruses: 8616169
[run-freshclam-at-first] Engine version: 0.103.5
[run-freshclam-at-first] Scanned directories: 32
[run-freshclam-at-first] Scanned files: 52
[run-freshclam-at-first] Infected files: 0
[run-freshclam-at-first] Data scanned: 0.11 MB
[run-freshclam-at-first] Data read: 0.05 MB (ratio 1.93:1)
[run-freshclam-at-first] Time: 26.566 sec (0 m 26 s)
[run-freshclam-at-first] Start Date: 2022:05:10 11:57:28
[run-freshclam-at-first] End Date:   2022:05:10 11:57:54
```

The clone-git step won't be there in production, it is being clonned as part of a pipeline.