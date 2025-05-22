# 💼 JobConnect

**JobConnect** is a job-seeking platform that connects job seekers with Talent Acquisition Managers. It uses machine learning algorithms to recommend jobs to seekers and suitable candidates to recruiters based on provided constraints.

## 🔍 Features
- ML-based job and candidate recommendations with recommendation percentages
- In-app job application and response system (no third-party software needed)
- Account-based login system for both seekers and recruiters
- Recruiters can accept or reject applications; seekers are notified accordingly

## ⚙️ Installation

1. **Compile the C files** using either:
   ```bash
   make
   ```
   or
   ```bash
   gcc main.c seeker.c company.c recommend_jobs.c recommend_seekers.c ScoreCalculation/score.c applications.c validation.c sha256.c -o app
   ```

2. **Run the application**:
   ```bash
   ./app
   ```

> ✅ **Note**: Ensure your terminal is in the correct directory before compiling. Use `cd` to navigate.

## 🧑‍💼 Usage

- Register as a job seeker or Talent Acquisition Manager.
- Seekers see recommended jobs with match percentages.
- Recruiters see recommended candidates.
- Seekers can apply to jobs directly.
- Recruiters can accept/reject applications.
- Application statuses are updated when users log in.

## ⚠️ Important
Do **not** modify or delete any `.dat` files. These are used to store critical application data.

## 👨‍💻 Authors
- Shaun Allan. H — 3122 22 5001 127  
- Saisandeep Sangeetham — 3122 22 5001 119  
- Shreyamanisha C. Vinay — 3122 22 5001 130
