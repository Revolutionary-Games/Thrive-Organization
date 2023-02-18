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
- [ ] Run `dotnet run --project Scripts -- translation-progress`
- [ ] Make sure save upgrade steps are added (if save breakage is not planned)
- [ ] Make a release candidate and post on the community forums and discord (use DevCenter file hosting for the downloads)
- [ ] Upload RC also to beta channel on game stores (with [ThriveStoreScripts](https://github.com/Revolutionary-Games/ThriveStoreScripts))
- [ ] Post an announcement on Steam about the RC and upcoming release
- [ ] Post announcement on Weblate when deadline for translations is (2 days before the release at the end of the day)
- [ ] Post on Patreon about the RC
- [ ] Enable the auto comment on PRs about feature freeze
- [ ] Start drafting the release on Github
- [ ] Post the patch notes draft on discord so that devblog can start
- [ ] Get someone (or our usual trailer guy) to start working on a trailer
- [ ] Make a livestream event on Youtube if there are probably enough people for it. Optional: make pre-stream questions for general audience (max 3 questions per person)
- [ ] Make high priority questions thread for the VIP patrons (max 7 questions per person), post on Patreon a general stream announcement and link the question threads
- [ ] Get someone to start writing the devblog
- [ ] 1 day before release: merge last small fix PRs
- [ ] Merge last translations PR (first push all pending changes from weblate)
- [ ] Update patch notes in the Thrive repo (`simulation_parameters/common/patch_notes.yml`)
- [ ] Make sure trailer is ready to go
- [ ] Run `dotnet run --project Scripts -- translation-progress`
- [ ] Update credits with `dotnet run --project Scripts -- credits`
- [ ] Add save upgrade step from RC to the full release (if save breakage is not planned)
- [ ] On the day of release: compile and upload builds to Github release draft
- [ ] Push the release version to the stable channel for game stores
- [ ] Publish the release on Github
- [ ] Update the launcher data on DevCenter to have the new version listed in the launcher
- [ ] Publish the trailer on our Youtube channel
- [ ] Publish the devblog
- [ ] Post the devblog (and trailer) on our subreddit
- [ ] Post on steam. Needs an 800x450 preview image
- [ ] Post on Itch. Can copy-paste the first part of the devblog and link the rest
- [ ] Link the release on Github to the devblog and link the trailer in the devblog
- [ ] Post @everyone announcement with the devblog on community discord
- [ ] After the release: turn the auto comment to Github off
- [ ] Post general feedback thread on the community forums
- [ ] Have the release livestream
