<!--
#
# Licensed to the Apache Software Foundation (ASF) under one
# or more contributor license agreements.  See the NOTICE file
# distributed with this work for additional information
# regarding copyright ownership.  The ASF licenses this file
# to you under the Apache License, Version 2.0 (the
# "License"); you may not use this file except in compliance
# with the License.  You may obtain a copy of the License at
#
# http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing,
# software distributed under the License is distributed on an
# "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
#  KIND, either express or implied.  See the License for the
# specific language governing permissions and limitations
# under the License.
#
-->

# Release Notes

### 0.2.1 (Sept 5, 2013)

- CB-4432 copyright notice change

### 0.2.3 (Sept 25, 2013)

- CB-4889 bumping&resetting version
- [windows8] commandProxy was moved
- CB-4889 renaming references
- CB-4889 renaming org.apache.cordova.core.media to org.apache.cordova.media
- [CB-4847] iOS 7 microphone access requires user permission - if denied, CDVCapture, CDVSound does not handle it properly
- Rename CHANGELOG.md -> RELEASENOTES.md
- [CB-4799] Fix incorrect JS references within native code on Android & iOS
- Fix compiler/lint warnings
- Rename plugin id from AudioHandler -> media
- [CB-4763] Remove reference to cordova-android's FileHelper.
- [CB-4752] Incremented plugin version on dev branch.

### 0.2.4 (Oct 9, 2013)

- [CB-4928] plugin-media doesn't load on windows8
- [CB-4915] Incremented plugin version on dev branch.

### 0.2.5 (Oct 28, 2013)

- CB-5128: add repo + issue tag to plugin.xml for media plugin
- [CB-5010] Incremented plugin version on dev branch.

### 0.2.6 (Dec 4, 2013)

- [ubuntu] specify policy_group
- add ubuntu platform
- Added amazon-fireos platform. Change to use amazon-fireos as a platform if the user agent string contains 'cordova-amazon-fireos'

### 0.2.7 (Jan 02, 2014)

- CB-5658 Add doc/index.md for Media plugin
- Adding READ_PHONE_STATE to the plugin permissions

### 0.2.8 (Feb 05, 2014)

- Add preliminary support for Tizen.
- [CB-4755] Fix crash in Media.setVolume on iOS

### 0.2.9 (Feb 26, 2014)

- CB-6051 Update media plugin to work with new cdvfile:// urls
- CB-5748 Make sure that Media.onStatus is called when recording is started.

### 0.2.10 (Apr 17, 2014)

- CB-6422: [windows8] use cordova/exec/proxy
- CB-6212: [iOS] fix warnings compiled under arm64 64-bit
- CB-6225: Specify plugin dependency on File plugin 1.0.1
- CB-6460: Update license headers
- CB-6465: Add license headers to Tizen code
- Add NOTICE file

### 0.2.11 (Jun 05, 2014)

- CB-6127 Spanish and French Translations added. Github close #13
- CB-6807 Add license
- CB-6706: Relax dependency on file plugin
- CB-6478: Fix exception when try to record audio file on windows 8
- CB-6477: Add musicLibrary and microphone capabilities to windows 8 platform
- CB-6491 add CONTRIBUTING.md

### 0.2.12 (Aug 06, 2014)

- CB-6127 Updated translations for docs
- ios: Make it easier to play media and record audio simultaneously
- code #s for MediaError

### 0.2.13 (Sep 17, 2014)

- CB-6963 renamed folder to tests + added nested plugin.xml
- added documentation for manual tests
- CB-6963 Port Media manual & automated tests
- CB-6963 Port media tests to plugin-test-framework

### 0.2.14 (Oct 03, 2014)

- Amazon Specific changes: Added READ_PHONE_STATE permission same as done in Android
- make possible plays wav file
- CB-7638 Get audio duration properly on windows
- CB-7454 Adds support for m4a audio format for Windows
- CB-7547 Fixes audio recording on windows platform
- CB-7531 Fixes play() failure after release() call

### 0.2.15 (Dec 02, 2014)

- CB-6153 **Android**: Add docs for volume control behaviour, and fix controls not being reset on page navigation
- CB-6153 **Android**: Make volume buttons control music stream while any audio players are created
- CB-7977 Mention `deviceready` in plugin docs
- CB-7945 Made media.spec.15 and media.spec.16 auto tests green
- CB-7700 cordova-plugin-media documentation translation: cordova-plugin-media

### 0.2.16 (Feb 04, 2015)

- CB-8351 ios: Stop using (newly) deprecated CDVJSON.h
- CB-8351 ios: Use argumentForIndex rather than NSArray extension
- CB-8252 android: Fire audio events from native via message channel
- CB-8152 ios: Remove deprecated methods in Media plugin (deprecated since 2.5)

### 1.0.0 (Apr 15, 2015)

- CB-8793 Fixed tests to pass on wp8 and windows
- CB-8746 bumped version of file dependency
- CB-8746 gave plugin major version bump
- CB-8779 Fixed media status reporting on wp8
- CB-8747 added missing comma
- CB-8747 updated dependency, added peer dependency
- CB-8683 changed plugin-id to pacakge-name
- CB-8653 properly updated translated docs to use new id
- CB-8653 updated translated docs to use new id
- CB-8541 Adds information about available recording formats on Windows
- Use TRAVIS_BUILD_DIR, install paramedic by npm
- CB-8686 - remove musicLibrary capability
- CB-7962 Adds browser platform support
- CB-8653 Updated Readme
- CB-8659: ios: 4.0.x Compatibility: Remove use of deprecated headers
- CB-8572 Integrate TravisCI
- CB-8438 cordova-plugin-media documentation translation: cordova-plugin-media
- CB-8538 Added package.json file
- CB-8428 Fix tests on Windows if no audio playback hardware is available
- CB-8428 Fix multiple `done()` calls in media plugin test on devices where audio is not configured
- CB-8426 Add Windows platform section to Media plugin
- CB-8425 Media plugin .ctr: make src param required as per spec

### 2.3.1 (Dec 09, 2022)

- removed code block to access native iOS file, userAgent missing in Cordova iOS 6.2.0, causing compile errors
- revised plugin id to sync with repository name for naming consistency
- revised file plugin dependency to v4.33 or >

### 2.3.2 (Oct 11, 2023)

- revised Android permission logic to handle changes for API level 33
