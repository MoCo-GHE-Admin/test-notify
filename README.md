# Done
- [x] Create `CODEOWNERS` with `@moco-ghe-admin/test-notify` team owning everything
- [x] have a mortal not on the team create PR #1

# To Do
- [ ] verify that mortal team maintainer gets notified of PR #1
- [ ] mortal-not-on-team makes a change to the PR #1
- [ ] verify that mortal-team-maintainer gets notified of PR #1 change
  - if not notified, mortal-not-on-team makes PR #2
- [ ] mortal team maintainer adds an ignore for this repo to their notifications settings
- [ ] mortal-not-on-team generates another PR event (either a change or PR #3)
- [ ] mortal-team-maintainer verifies no notification received.

I think that's it -- we may want to add a mortal-not-maintainer to the team (andy?) and then do another round of PR event generation for completeness
