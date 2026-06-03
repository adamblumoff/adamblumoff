## What I'm working on right now
  - Lane (not public yet): Git worktrees help agents work in parallel, but the UX is wrong: copying repos, syncing config, and juggling branches is directory-level choreography for what is really a file-level problem. Files should support multiple writers directly. Lane gives each agent its own view of the same path: `File(path, lane) -> bytes`. Agents edit normal files in the normal repo, but their changes land in separate lanes, so they can destructively rewrite the same file without overwriting each other. When one direction wins, you explicitly promote it back to base. Parallel coding becomes a file primitive, not a folder management problem. This is still a work in progress and not good enough to release yet, but it's pretty cool!!

## Other Projects
  - [Promptreel](https://github.com/adamblumoff/promptreel): Visualization of a repo's history through prompt events, kind of like GitHub, but the main primitive is a prompt, not a            commit. Working on cloud and local versions right now. 
  - [Gym-Motion](https://github.com/adamblumoff/gym-motion): A proof of concept for monitoring activity across gym machines through a simple local gateway, Bluetooth-connected nodes, and      a centralized dashboard, designed to make equipment analytics more affordable and practical for gym operators. POC is there, working on the final form factor and getting the hardware      MVP started. 
  - [CareBase](https://github.com/adamblumoff/carebase): A caregiver coordination app that centralizes appointments, bills, and notes to reduce information overload
    and caregiver burnout.
  - [DebateBench](https://github.com/adamblumoff/debate-bench): A Python-based LLM debate platform with reproducible runs, structured artifacts, automated scoring,
    and a server-rendered analytics dashboard for performance and cost analysis.
  - [Student Success Prediction](https://github.com/adamblumoff/student-success-prediction): A machine learning platform that identifies at-risk K-12 students early
    using an explainable neural network and integrated intervention dashboards.
  - [Othello Game Engine](https://github.com/adamblumoff/OthelloEngine): A competitive Othello AI project comparing alpha-beta search and Q-learning, including a c
    o-authored paper on the results.

## Recent Technologies and Tools

T3 stack (not exactly, but you get the point), Rust (definetly not proficient yet), Python, React Native, Expo, PostgreSQL, S3, Railway, Codex (the goat)

## Contact

Email: adamblumoff@gmail.com

Website: www.blumey.dev (info is probably out of date)

LinkedIn: www.linkedin.com/in/adam-blumoff (also probably out of date)










































