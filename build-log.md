# ReputationSync build log

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
