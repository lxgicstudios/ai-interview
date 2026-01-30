# ai-interview

[![npm version](https://img.shields.io/npm/v/ai-interview.svg)](https://www.npmjs.com/package/ai-interview)
[![npm downloads](https://img.shields.io/npm/dm/ai-interview.svg)](https://www.npmjs.com/package/ai-interview)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/lxgic-studios/ai-interview)](https://github.com/lxgic-studios/ai-interview/stargazers)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-blue)](https://www.typescriptlang.org/)



Generate interview questions tailored to your actual codebase. Great for hiring people who'll work on your specific stack.

## Install

```bash
npm install -g ai-interview
```

## Usage

```bash
npx ai-interview ./src/
# → 10 mid-level questions based on your code

npx ai-interview ./src/ --level senior --count 15
# → 15 senior-level questions

npx ai-interview ./src/ -o questions.md
# → Save to file
```

## Setup

```bash
export OPENAI_API_KEY=sk-...
```

## Options

- `-l, --level` - junior, mid, or senior (default: mid)
- `-n, --count` - Number of questions (default: 10)
- `-o, --output` - Save questions to a file

## License

MIT
