Do this to generate your change history

  git log --pretty=format:'  * %h - %s (%an, %ad)' vX.Y.Z..HEAD

### 1.1.4 (28 July 2017)
* 41ddcbd - chore(gems): Update gems (Beth Skurrie, Fri Jul 28 16:24:45 2017 +1000)

### 1.1.3 (02 June 2017)
* 066fa60 - Add states list to state setup JSON body, to prepare for v3 pact spec which allows multiple provider states (Beth Skurrie, Fri Jun 2 15:01:28 2017 +1000)

### 1.1.2 (02 June 2017)
* da958c0 - Only set up state if a provider-states-setup-url is provided. Add tests for SetUpProviderState. (Beth Skurrie, Fri Jun 2 14:31:27 2017 +1000)
* 36ef2eb - Remove .java, .class, .gitignore and .travis.yml files from package (Beth Skurrie, Fri Jun 2 10:32:55 2017 +1000)
* 7902674 - Add rake tasks to generate and upload release notes. (Beth Skurrie, Fri Jun 2 10:12:17 2017 +1000)
* 01e811e - Add integration specs for command (Beth Skurrie, Fri Jun 2 05:51:30 2017 +1000)

### 1.1.0 (01 June 2017)
* 7106832 - chore(docs): update docs for provider states URL (Matt Fellows, Fri May 26 22:45:09 2017 +1000)
* 8f787e6 - Add deprecation warning for --provider-states-url (Beth Skurrie, Fri May 26 20:51:48 2017 +1000)
* 982ba7c - Remove need for provider-states-url by dynamically calling the set up code during test execution (Beth Skurrie, Fri May 26 16:30:14 2017 +1000)
* f055375 - Turn silent mode on for zip task in rake package (Beth Skurrie, Tue May 23 09:34:51 2017 +1000)

### 1.0.2 (23 May 2017)
* 33f0811 - Upgrade rspec version to ~>3.5 to fix #11 (Beth Skurrie, Tue May 23 09:01:07 2017 +1000)

### 1.0.1 (9 May 2017)
* 94597a0 - Updated pact gem to allow use of https for publishing verifications (Beth Skurrie, Tue May 9 14:27:19 2017 +1000)

### 1.0.0 (9 May 2017)

### 0.0.4 (15 May 2016)

* c5dc292 - Added basic authentication support for Pact Broker URLs (Matt Fellows, Sun May 15 19:08:22 2016 +1000)

### 0.0.3 (15 May 2016)

* d36ae19 - Release v0.0.3 (Matt Fellows, Sun May 15 11:22:41 2016 +1000)

### 0.0.2 (12 May 2016)

* 0aca507 - Refactored to not use the Pact rake tasks. Traveling Ruby does not like shelling out to a Ruby process (where's my Gems?) (Matt Fellows, Thu May 12 21:55:29 2016 +1000)
* 9feb60e - Verifier properly runs all Pacts provided and handles Pact CLI exit call (Matt Fellows, Sun May 15 11:22:12 2016 +1000)
* a85903d - Release template (Matt Fellows, Thu May 12 21:53:22 2016 +1000)
* 059b488 - Setting execute perms on wrapper script during package (Matt Fellows, Thu May 12 22:30:22 2016 +1000)

### 0.0.1 (8 May 2016)

* 39e75f3 - Pact provider verifier cross-platform CLI tool (Matt Fellows, Thu May 12 07:30:47 2016 +1000)
