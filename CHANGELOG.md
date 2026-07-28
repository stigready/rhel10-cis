# Changelog

Format based on [Keep a Changelog](https://keepachangelog.com/).

## [0.2.1-private-review] - export review

### Added
- Initial StigForge export of matrix role `rhel10_cis`.
- OpenSCAP verify evidence bundles per profile under `compliance/releases/`.

### Verified (CI)

- **`cis-l1`** — score **92.0%** (floor 90.0%) · gate **PASS** · evidence `20260726T135946Z`
  - OpenSCAP failures still counted: `accounts_password_pam_modules_in_authselect_profile, accounts_umask_etc_bashrc, accounts_umask_etc_profile, configure_custom_crypto_policy_cis, file_permissions_ungroupowned, use_pam_wheel_group_for_su`
- **`cis-l2`** — score **92.21%** (floor 90.0%) · gate **PASS** · evidence `20260726T140034Z`
  - OpenSCAP failures still counted: `accounts_password_pam_modules_in_authselect_profile, accounts_umask_etc_bashrc, accounts_umask_etc_profile, configure_custom_crypto_policy_cis, file_permissions_ungroupowned, use_pam_wheel_group_for_su`

### Provenance

- Factory pipeline: https://github.com/stigready/stigforge/actions/runs/30277229616
- Factory commit: `f0323b6e2f0f36a0418447b9859a0576278541b8`

