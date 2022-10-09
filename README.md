# Auto-Git-Pull

A tool for auto-pulling/merging repos using git2.

## Getting started
1. Setup:
```
cp .env.example .env
cp repos.txt.example repos.txt
```
2. Replace repos in repos.txt
3. Add repos' save dest to .env
4. Compile:
```
cargo build --release
```

## Known issues
* "corrupted loose reference file: FETCH_HEAD" with some repos
* No OAuth/SSH/etc authentication available

## License
[MIT](https://github.com/abrandec/auto-git-pull/blob/main/MIT-LICENSE.txt)