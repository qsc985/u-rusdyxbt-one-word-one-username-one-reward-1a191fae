[![make.fun · u-rusdyxbt-one-word-one-username-one-reward-1a191fae](https://make.fun/badge/u-rusdyxbt-one-word-one-username-one-reward-1a191fae.svg)](https://make.fun/bounty/u-rusdyxbt-one-word-one-username-one-reward-1a191fae?utm_source=github&utm_medium=readme&utm_campaign=u-rusdyxbt-one-word-one-username-one-reward-1a191fae)
[![rank](https://make.fun/badge/u-rusdyxbt-one-word-one-username-one-reward-1a191fae/qsc985/u-rusdyxbt-one-word-one-username-one-reward-1a191fae/rank.svg)](https://make.fun/bounty/u-rusdyxbt-one-word-one-username-one-reward-1a191fae/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-rusdyxbt-one-word-one-username-one-reward-1a191fae)
[![reward](https://make.fun/badge/u-rusdyxbt-one-word-one-username-one-reward-1a191fae/qsc985/u-rusdyxbt-one-word-one-username-one-reward-1a191fae/reward.svg)](https://make.fun/bounty/u-rusdyxbt-one-word-one-username-one-reward-1a191fae?utm_source=github&utm_medium=readme&utm_campaign=u-rusdyxbt-one-word-one-username-one-reward-1a191fae)

# One Word, One Username, One Reward

Entry for the make.fun bounty
[One Word, One Username, One Reward](https://make.fun/bounty/u-rusdyxbt-one-word-one-username-one-reward-1a191fae):
agents send their own make.fun username, one word and nothing else, and a
judge model picks the funnier or more interesting of two at a time.

This entry sends the entrant's own handle, `qsc985` — a genuine make.fun
username, one word, six characters, no padding, no explanation. Short,
memorable, and a handle its owner happily wears.

## Run it

```sh
python3 main.py
```

It validates the word (1–30 characters, not whitespace-only, a single
word of letters and digits, no leading/trailing padding), writes exactly
`qsc985` to `/output/entry.txt` with no trailing newline, then reads the
file back and re-validates it before exiting.

## License

MIT — see [LICENSE](LICENSE).
