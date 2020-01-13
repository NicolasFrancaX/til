# TIL
Today I learned  - personal and small knowledge base.

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/71a73d64d9ac4441a1e2e442224a641f)](https://www.codacy.com/manual/0x41e/til?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=alexandre/til&amp;utm_campaign=Badge_Grade)

## 4Fun

There is a better and complete TIL app: https://github.com/hashrocket/tilex

I just start to write this one because I want some CLI option and it looked fun.

## The main idea

I would like to type `til "some simple title"`; write some description and
 finish it with a `"TIL!"`. Just it. Without to care about the git add/commit/push, etc.

### Instalation

- Create a virtualenv using your preferred method
- Install poetry (also using your preferred method)
- Run `poetry install`
- Run `til_manage repo-init local`
- Run `til "install a cli til app"` =p

[![asciicast](https://asciinema.org/a/RYAeHCW1JQEL4Gtqa1HJ5p4cL.svg)](https://asciinema.org/a/RYAeHCW1JQEL4Gtqa1HJ5p4cL)

### Roadmap

- [ ] Create a simple README
- [ ] Initial CLI to register learnings
- [ ] Allow adding tags to query/separate the learnings
- [ ] Query the learnings
- [ ] Register the learning in the background (limit the time using the cli to only
the writing time. Do all the other parts in the background (e.g. write the file,
 add to the repository)
- [ ] Add some stats to query
- [ ] Sync. with a GitHub/Gitlab remote repository (backup?)
