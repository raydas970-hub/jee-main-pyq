# JEE Main Previous Year Questions (2016-2026)

This repository contains a comprehensive collection of JEE Main previous year questions from 2016 to 2026 in JSON format.

## Overview

JEE Main (Joint Entrance Examination) is one of India's most competitive engineering entrance exams. This repository provides organized access to previous year questions across multiple years.

## Repository Structure

```
jee-main-pyq/
├── README.md
├── SCHEMA.md
├── 2016/
│   ├── january.json
│   └── april.json
├── 2017/
│   ├── january.json
│   └── april.json
├── 2018/
│   ├── january.json
│   └── april.json
├── 2019/
│   ├── january.json
│   └── april.json
├── 2020/
│   ├── january.json
│   ├── july.json
│   └── september.json
├── 2021/
│   ├── february.json
│   ├── march.json
│   ├── july.json
│   └── august.json
├── 2022/
│   ├── june.json
│   ├── july.json
│   └── august.json
├── 2023/
│   ├── january.json
│   └── april.json
├── 2024/
│   ├── january.json
│   └── april.json
├── 2025/
│   ├── january.json
│   └── april.json
├── 2026/
│   ├── january.json
│   └── april.json
└── samples/
    └── sample-question.json
```

## File Format

Each JSON file contains questions organized by subject and difficulty level. See `SCHEMA.md` for detailed format specifications.

## Subjects Covered

- Physics
- Chemistry
- Mathematics

## Difficulty Levels

- Easy
- Medium
- Hard

## Usage

Clone the repository:
```bash
git clone https://github.com/raydas970-hub/jee-main-pyq.git
```

Navigate to the desired year and month:
```bash
cd 2024/january.json
```

## JSON Schema

Each question object contains:
- `id`: Unique question identifier
- `year`: Year of the exam
- `month`: Month/Session of the exam
- `subject`: Subject (Physics/Chemistry/Mathematics)
- `difficulty`: Difficulty level
- `question`: Question text
- `options`: Array of options (A, B, C, D)
- `correctAnswer`: Correct option
- `explanation`: Detailed explanation
- `marks`: Marks assigned

## Contributing

Contributions are welcome! Please ensure data accuracy and follow the JSON schema format.

## License

This repository is for educational purposes. Please respect copyright laws and official JEE Main resources.

## Disclaimer

This is an unofficial repository created for educational reference. The actual exam content and official questions belong to NTA (National Test Agency).

---

**Last Updated**: March 15, 2026