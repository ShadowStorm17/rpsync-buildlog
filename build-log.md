# ReputationSync build log

### 2026-10-29
- Worked on: deciding how to rank stories: those already believed come first, then those catching up fast, then open questions.
- What broke / was hard: the test of yesterday's memory change found fewer tiny new stories, and nobody can yet say if they were real.
- Decided NOT to build: a trained ranking model; with one week of history it would only guess, so simple visible rules come first.
- Lesson or surprise: a reply from the brand does not end a story; it often starts a new chapter worth watching.

### 2026-10-28
- Worked on: checking five days of real daily history, and teaching the system to remember yesterday's work instead of starting fresh each morning.
- What broke / was hard: small stories appeared one day and vanished the next; the AI picks slightly differently from the same news.
- Decided NOT to build: asking the AI to "remember" a list of stories; reusing our own saved links is steadier, cheaper and lasts longer.
- Lesson or surprise: a fair test needs examples neither version has seen; our first comparison looked perfect only because the answers were memorised.

### 2026-10-23
- Worked on: giving ReputationSync a memory: every analysis is kept, stories are followed day by day, and two brands now run automatically each morning.
- What broke / was hard: deciding what to do when storage is down; saving the run for later would have quietly created duplicate stories.
- Decided NOT to build: forecasts of where a story will be in a week; they wait until real history can prove them right.
- Lesson or surprise: trust should mean "was this source right?", not "is it popular?"; a small outlet can be early and correct.

### 2026-10-12
- Worked on: checking our "who is driving this story" judgements against careful human reading of 66 real examples, then fixing the gaps.
- What broke / was hard: a quiet timing bug made one live analysis skip a quarter of its news, including its most serious story.
- Decided NOT to build: treating guesses as facts; a likely copied article is now labelled "probably copied", with lower confidence.
- Lesson or surprise: users lose patience fast; saving each analysis for six hours turned a five-minute wait into an instant answer.

### 2026-10-11
- Worked on: every story now shows who is driving it: who started it, which trusted sources endorse it, who disputes it.
- What broke / was hard: LinkedIn looked like a top authority, because the platform is popular, until we credited posts to their authors.
- Decided NOT to build: our own AI model to judge trust; simple track-record counting over time is cheaper and explains itself.
- Lesson or surprise: real data caught problems that tidy test examples never showed, like a re-posting site ranked as a story's top driver.

### 2026-10-06
- Worked on: designing how ReputationSync tells who is driving a story: who started it, who endorsed it, who only repeated it.
- What broke / was hard: the free website-ranking list we planned to use turned out to be non-commercial only, so we switched sources.
- Decided NOT to build: asking AI to judge how trustworthy a source is; we use measurable, free public signals instead.
- Lesson or surprise: "free data" often comes with licence strings attached; checking before building saved us from a rewrite later.
