# Done
- [x] Create `CODEOWNERS` with `@moco-ghe-admin/test-notify` team owning everything
- [x] have a mortal not on the team create PR #1
- [X] verify that mortal team maintainer gets notified of PR #1
- [X] verify that mortal-on-team has write to the repo (hwine)
  - hwine doesn't think this matters.
- [x] mortal-not-on-team makes a change to the PR #1
- [x] verify that mortal-team-maintainer gets notified of PR #1 change
  - if not notified, mortal-not-on-team makes PR #2

# To Do

- [X] mortal team maintainer adds an ignore for this repo to their notifications settings
  - cknowles-moz did it my going to subscribed repos and setting to ignore all
  - [X] There are various ways, according to [item 3 here](https://docs.github.com/en/account-and-profile/managing-subscriptions-and-notifications-on-github/managing-subscriptions-for-activity-on-github/managing-your-subscriptions#unwatching-repositories). We might have to make several tries. I think changes made by immortals to this PR should trigger notifications to a mortal. If true, that'll shorten the retry time.
- [X] immortal (cknowles-admin) makes a change (This one!)
- [X] mortal (cknowles-moz) does NOT receive any notification
- [ ] mortal-not-on-team generates another PR event (either a change or PR #3)
- [ ] mortal-team-maintainer verifies no notification received.

I think that's it -- we may want to add a mortal-not-maintainer to the team (andy?) and then do another round of PR event generation for completeness
