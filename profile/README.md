# Centre for Educational Technology / Haridustehnoloogia keskus  🎓

![preview](https://github.com/centre-for-educational-technology/.github/raw/master/preview.png)

## About us

Centre for Educational Technology is the research centre of the School of Digital Technology, Tallinn University (TLU). Centre was established 25 years ago and is now one of the leading competency-centres in technology-enhanced learning in Estonia.

The Centre focuses on theoretical, methodological and practical questions related to educational uses of technologies for teaching and learning in formal and informal educational settings. Our centre investigates the development, adoption and use of technologies in several areas of society with the data-driven focus. Special emphasis is put on technologies in education and industry.

The centre encourages highly links between research and teaching. Our teaching is research-led and research is informed by our teaching. We involve our MA and PhD students in our projects and research activities. Our teaching programs on MA level are international level programs: Digital Learning Games and Open Society Technologies and local programs Educational Technology and Teacher for Informatics. Also is center actively collaborating with the Estonian schools to pilot research-based solutions and methodologies and policy makers from HarNo to integrate our research results to policy actions.

Our international team consists of professors, associate professors, lecturers, junior researchers, developers and other project specialists who are working in our research groups.

More about us on our [website](https://web.htk.tlu.ee/htk/).

## Coding & Development Guidelines

Effective coding & development guidelines are crucial for researchers and  developers to ensure consistent, maintainable, and high-quality code and project maintaining process. These guidelines provide a set of best practices and standards that promote readability, modularity, and collaboration among staff of the CET (HTK). By following these guidelines:
- developers can improve code quality, reduce bugs, enhance performance, and make the codebase more scalable and maintainable
- researchers ... something. Project preparation phase should always include consultation round among researchers and developers in order to agree upon possible technical solutions, resources and timeframe.

### Tools and services we use

- Github - codebase
- Zone.ee - Our main hosting provider
- ...

### Version control

Utilize always [GitHub](https://github.com/centre-for-educational-technology), to track changes and collaborate other developers. Commit your code frequently and write descriptive commit messages.

#### Issues

If your repository is brand-new, you don’t have a lot of issues reported, and you want to enable all kinds and forms of feedback to flow in, just keep the default settings for your GitHub Issues. There’s one way to submit a feature request. There’s a different way to submit a bug. Discussions and support requests may or may not be welcome in your issue tracker. Consider dedicated service for discussions and feature requests (UserReport etc).

Mention other people if you want to use their expertise, have them provide an estimate, or just be aware of an issue. You can agree to set assignees immediately when new issues are created. This approach works as long as every possible reporter knows which developers should handle which issues.

Don’t forget to close issues. 

#### Branches

### Testing

Software testing involves the execution of a software component or system component to evaluate one or more properties of interes. In general, these properties indicate the extent to which the component or system under test:

- meets the requirements that guided its design and development,
- responds correctly to all kinds of inputs,
- performs its functions within an acceptable time,
- is sufficiently usable,
- can be installed and run in its intended environments, and
- achieves the general result its stakeholders desire.

### Documentation guidelines

- Documentation should be clear, concise and provide example on how the software is to be used
- Top level README file must contain all relevant information to get started using or developing of the project

### Sensitive data

Sensitive data includes things like passwords, usernames, server names, and data protected by law.

- Do not ever put sensitive data in files that are pushed to GitHub or made public in any other way.
- Some types of data may even only exist in certain folders or on certain machines. Do not proliferate this kind of data, not even internally. Also avoid putting this type of data in Dropbox, Google Drive or in similar cloud storage or shared network drive.
- If a password is published by mistake, you need to change the password (with everything that this entails). It is not enough to remove/reverse the commit or submit a new commit with the password removed.
- Code should use placeholders that point to:
  - Local read-protected files, possibly located outside of the Git repository file structure to avoid accidental inclusion as part of the repository,
  - Environment variables, or
  - Some sort of secured (possibly remote) storage.
- The documentation (README/INSTALL, whichever is most appropriate) should mention how to instantiate those variables/files, etc.
