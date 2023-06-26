# Centre for Educational Technology / Haridustehnoloogia keskus  🎓

![preview](https://github.com/centre-for-educational-technology/.github/raw/master/preview.png)

## About us

Centre for Educational Technology is the research centre of the School of Digital Technology, Tallinn University (TLU). Centre was established 25 years ago and is now one of the leading competency-centres in technology-enhanced learning in Estonia.

The Centre focuses on theoretical, methodological and practical questions related to educational uses of technologies for teaching and learning in formal and informal educational settings. Our centre investigates the development, adoption and use of technologies in several areas of society with the data-driven focus. Special emphasis is put on technologies in education and industry.

The centre encourages highly links between research and teaching. Our teaching is research-led and research is informed by our teaching. We involve our MA and PhD students in our projects and research activities. Our teaching programs on MA level are international level programs: Digital Learning Games and Open Society Technologies and local programs Educational Technology and Teacher for Informatics. Also is center actively collaborating with the Estonian schools to pilot research-based solutions and methodologies and policy makers from HarNo to integrate our research results to policy actions.

Our international team consists of professors, associate professors, lecturers, junior researchers, developers and other project specialists who are working in our research groups.

More about us on our [website](https://web.htk.tlu.ee/htk/).

## Coding Guidelines

Effective coding guidelines are crucial for web application developers to ensure consistent, maintainable, and high-quality code. These guidelines provide a set of best practices and standards that promote readability, modularity, and collaboration among developers. By following these guidelines, developers can improve code quality, reduce bugs, enhance performance, and make the codebase more scalable and maintainable.

### Version control

Utilize always GitHub, to track changes and collaborate other developers. Commit your code frequently and write descriptive commit messages.

```
Commit: Add user authentication functionality

Description:
This commit adds the user authentication functionality to the application. It includes the following changes:

- Implemented user registration and login functionality using the Passport.js library.
- Created user model and schema to store user information in the database.
- Added routes for user registration, login, and logout.
- Implemented password hashing and salting for secure storage of user passwords.
- Created middleware to handle user authentication and protect routes that require authentication.

This feature allows users to securely register, log in, and access protected areas of the application. It lays the foundation for implementing user-specific features and personalization in future updates.

Closes #123
```

In this example, the commit message provides a clear and concise summary of the changes introduced in the commit. The description elaborates on the specific modifications made, such as implementing user authentication functionality using the Passport.js library, creating user models and routes, and ensuring password security. Additionally, it mentions the purpose of this feature and how it sets the groundwork for future enhancements. Lastly, the commit message includes a reference to the related issue or task number (#123) that this commit addresses, helping to track and link commits to specific tasks or bug reports in the project management system.

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
