# Centre for Educational Technology / Haridustehnoloogia keskus  🎓

![preview](https://github.com/centre-for-educational-technology/.github/raw/master/preview.png)

## About us

Centre for Educational Technology is the research centre of the School of Digital Technology, Tallinn University (TLU). Centre was established 25 years ago and is now one of the leading competency-centres in technology-enhanced learning in Estonia.

The Centre focuses on theoretical, methodological and practical questions related to educational uses of technologies for teaching and learning in formal and informal educational settings. Our centre investigates the development, adoption and use of technologies in several areas of society with the data-driven focus. Special emphasis is put on technologies in education and industry.

The centre encourages highly links between research and teaching. Our teaching is research-led and research is informed by our teaching. We involve our MA and PhD students in our projects and research activities. Our teaching programs on MA level are international level programs: Digital Learning Games and Open Society Technologies and local programs Educational Technology and Teacher for Informatics. Also is center actively collaborating with the Estonian schools to pilot research-based solutions and methodologies and policy makers from HarNo to integrate our research results to policy actions.

Our international team consists of professors, associate professors, lecturers, junior researchers, developers and other project specialists who are working in our research groups.

More about us on our [website](https://web.htk.tlu.ee/htk/).

## Coding & Development Guidelines

Our goal is to keep CET/HTK projects consistent, maintainable and secure. These guidelines support efficient collaboration between researchers, developers and project partners.

Before starting a new technical project, researchers and developers should have an early planning/consultation round to clarify technical choices, resources and timeline.

### Tools and services we use

- GitHub – version control, issue tracking, code reviews
- Zone.ee – primary hosting
- Other services may be used as needed, but should be agreed within the team.

### Tools and services we use

- Do not add external people to CET/HTK GitHub organisation or repositories without approval from the unit lead or technical lead.
- Avoid granting unnecessary permissions. Use the least-privilege principle.
- Use teams and role-based access instead of ad-hoc individual permissions.

## Version control

### General Workflow

- Always use our GitHub organisation: https://github.com/centre-for-educational-technology
- Commit regularly with clear, descriptive commit messages.
- Keep commits small and focused.

### Branching

- Use a simple flow:
    - main – stable, production-ready
    - dev (optional) – integration/testing
    - **feature/**name – short-lived feature branches

- Open a Pull Request for all changes to main. Use PRs for code review and discussion.

### Issues

- Use GitHub Issues to track bugs, tasks and feature requests.
- Keep issue titles short and clear; describe the problem, not just the solution.
- Assign issues only to relevant people.
- Mention others when their expertise is needed.
- Close issues when resolved.

## Testing

- Each project should include a minimal testing approach appropriate for its size.
- Automated tests are recommended for production code.
- At minimum, ensure that:
    - core functionality works as intended
    - software behaves correctly with typical and edge-case inputs
    - basic performance and usability expectations are met

## Documentation Guidelines

- Every repository must have a top-level README describing:
    - purpose of the project
    - how to install/run it
    - basic development workflow
    - any configuration needed (env variables, secrets, etc.)
- Document code consistently:
    - keep comments short and meaningful
    - include inline documentation for complex logic
    - maintain clear folder structure
- Provide short examples of how to use the software, API, or datasets.

## Handling Sensitive Data

- Never commit sensitive data (passwords, private keys, tokens, server details, personal data).
- If sensitive data leaks, rotate the password/token immediately. Removing commits is not enough.
- Use:
    - environment variables
    - <code>.env</code> files excluded via <code>.gitignore</code>
    - secure remote storage or secret managers
    - Document how to set up local configuration without exposing secrets.
