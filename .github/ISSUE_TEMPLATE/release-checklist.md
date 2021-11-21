---
name: Release Checklist
about: Checklist for new Thrive releases
title: Release checklist for x.y.z.w
labels: outreach, project management
assignees: ''

---

Checklist for Thrive release (these should roughly happen in order):

- [ ] 9 days before release: check open PRs to see if any is close enough to done so that they can be pushed to be finished
- [ ] Ask on discord if people are up for a release podcast
- [ ] Mention on discord that feature freeze has started
- [ ] 7 days before release: merge open PRs from weblate (first push all pending changes from weblate)
- [ ] Run scripts/update_translation_progress.rb
- [ ] Make a release candidate and post on the community forums and discord (use DevCenter file hosting for the downloads)
- [ ] Upload RC also to beta channel on game stores
- [ ] Post announcement on Weblate when deadline for translations is (2 days before the release at the end of the day)
- [ ] Enable the auto comment on PRs about feature freeze
- [ ] Start drafting the release on Github
- [ ] Post the patch notes draft on discord so that devblog can start
- [ ] Get someone (or our usual trailer guy) to start working on a trailer
- [ ] Make a livestream event on Youtube if there are probably enough people for it
- [ ] 1 day before release: merge last small fix PRs
- [ ] Merge last translations PR (first push all pending changes from weblate)
- [ ] Make sure trailer is ready to go
- [ ] Run scripts/update_translation_progress.rb
- [ ] Update credits with scripts/retrieve_credits.rb
- [ ] On the day of release: compile and upload builds to Github release draft
- [ ] Push the release version to the stable channel for game stores
- [ ] Publish the release on Github
- [ ] Update the launcher repo to have the new version listed in the launcher
- [ ] Publish the trailer on our Youtube channel
- [ ] Publish the devblog
- [ ] Link the release on Github to the devblog and link the trailer in the devblog
- [ ] Have the release livestream