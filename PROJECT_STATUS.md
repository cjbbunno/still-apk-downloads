# Still project status

Checked: 8 November 2026 (Australia/Perth).

## Google Play testing readiness

Checked in the signed-in Black Tide Labs Play Console on 9 November 2026 (Australia/Perth).

- No Still application record exists. The account currently lists Debt Goblin, Sub-Text, and OWNERSELL only.
- There is no existing Still test track, package record, tester list, or prior uploaded bundle to continue.
- The available Still artifact is an APK. Google Play test tracks require a versioned Android App Bundle (`.aab`) created from the application project; the APK cannot safely substitute for a Play-upload bundle.
- Creating a new Play app record and uploading a new bundle require a verified application ID, source build, version-code plan, original signing/upload-key compatibility, and the required Play declarations. These are not available in the release repository.

## Verified

- This repository is an APK distribution repository. Before this checkpoint, its only tracked file was README.md and its main commit was 57ad46922321ad0cad591ecb809c37eaf470559f.
- Live GitHub refs show main and tag v1.0.8-build9 at that commit.
- The locally saved Still 1.0.8 build 9 APK is 124,506,291 bytes. SHA-256: 7608fa8a98650ba6ced8197895329e47dc5b020ca78591a9c3bb28125860c42d.
- APK location: C:/Dev/Projects/App-Downloads/Current/Still/Still-1.0.8-build9.apk.
- APK ZIP inspection found assets/index.android.bundle (3,615,452 bytes), with a binary header. This compiled payload does not establish recovery of editable source, dependencies, or a reproducible build.

## Recovery searches

- Refreshed accessible GitHub repository inventory and searched repositories for Still. Only still-apk-downloads was identified by that name.
- Searched recovered project manifests and README/status records for Still application identifiers; no separate source project was identified.
- Searched Downloads, Documents and Desktop locations for Still-named files. No source archive was identified. The user Desktop directory was absent.
- Google Drive filename search for Still/still returned no results. The connector's search MIME restrictions mean this does not conclusively exclude ZIP source archives.
- Existing coordinated recovery records also identify Still editable source as an unresolved gap.

## Next action and blocker

Locate an original source archive, original development workspace, or historical chat/export identifying the build platform and source location. Check those before choosing reconstruction. No verified source location is currently known.

If original source cannot be recovered, scope a rebuild against the installed app after inspecting its screens and behaviour. A rebuild must not be represented as recovery of original source.

Before any replacement APK: verify original signing identity, preserve device data, and confirm update compatibility. No signing credentials are stored in this public repository.

## Release and backup boundaries

- Existing APK is preserved; no installation, runtime, payment, onboarding, or new release validation was performed in this checkpoint.
- No new app implementation, worker, schedule, deployment, or release was started.
- Local app downloads and history use the shared App-Downloads library. Its helper backup is a separate outstanding task; this checkpoint does not claim it is backed up here.
- Source development and launch remain blocked on source recovery or an agreed rebuild scope.
