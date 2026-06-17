# Agent Mode Prompt

Build the first version of CareerOps Command Center.

## Goal

Create a local-first React + Vite + Tailwind web app for job-search workflow management.

## Core Requirement

The app must work without login using browser localStorage.

## Pages

1. Dashboard
2. Jobs
3. Referrals
4. Follow-ups
5. JD Analyzer
6. Resume Versions
7. Feedback
8. About

## MVP Features

- Add, edit, delete job applications
- Add, edit, delete referral contacts
- Generate referral messages using placeholders:
  - {first_name}
  - {company}
  - {role}
  - {job_link}
  - {custom_line}
- Copy generated message to clipboard
- Mark contact status manually
- Auto-suggest follow-up date after message is marked sent
- Show today’s follow-ups
- Add and manage resume versions
- Paste JD and calculate rule-based fit score
- Include sample demo data
- Store all data in localStorage
- Provide CSV import/export for jobs and contacts if possible
- Make UI clean, mobile-friendly, and simple

## Safety Constraints

- Do not automate LinkedIn sending
- Do not scrape LinkedIn, Naukri, Indeed, or any job portal
- Do not request user passwords or cookies
- Do not use paid AI APIs
- Do not claim hiring probability; only show fit score and apply/skip recommendation

## Tech

- React
- Vite
- Tailwind CSS
- localStorage
- No backend for this version

## Expected Output

- Working app
- Clean folder structure
- Reusable components
- README with setup instructions
- Sample data included
- Clear comments where needed