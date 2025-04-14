# Homework 10

## GitHub Action Status

![GitHub Actions Status](https://github.com/JaswanthKSnjit/homework9/actions/workflows/production.yml/badge.svg)

---

## Closed Issues

Below are the 6 resolved issues, each tracked, branched, and merged with necessary test cases and code changes:

| Issue | Description | Pull Request | Resolution Summary |
|-------|-------------|--------------|--------------------|
| [#1](https://github.com/JaswanthKSnjit/homework10/issues/1) | Fixed name mismatch issue during user registration | [PR #2](https://github.com/JaswanthKSnjit/homework10/pull/2) | Replaced generate_nickname() with user input-based nickname
| [#3](https://github.com/JaswanthKSnjit/homework10/issues/3) | Added name validator to restrict `admin`, `root`, `superuser` names | [PR #4](https://github.com/JaswanthKSnjit/homework10/pull/4) | Implemented a nickname validator that blocks names such as `admin`, `root`, `superuser` to prevent creation of accounts with elevated or misleading privileges.
| [#5](https://github.com/JaswanthKSnjit/homework10/issues/5) | Enforced unique email and nickname validation | [PR #6](https://github.com/JaswanthKSnjit/homework10/pull/6) | Enforced uniqueness constraints by adding logic that checks for duplicate email and nickname entries during user creation or update.
| [#7](https://github.com/JaswanthKSnjit/homework10/issues/7) Instructor Video Issue  | Fixed name mismatch between frontend & Swagger UI | [PR #8](https://github.com/JaswanthKSnjit/homework10/pull/8) | Fixed frontend and Swagger response discrepancies by replacing all instances of generate_nickname() with static examples that align with the frontend expectations.
| [#9](https://github.com/JaswanthKSnjit/homework10/issues/9) | Password validation (uppercase, special char, min length) | [PR #10](https://github.com/JaswanthKSnjit/homework10/pull/10) | Added strong password validation to enforce rules such as use of uppercase, special char, min length.
| [#11](https://github.com/JaswanthKSnjit/homework10/issues/11) | Validator for valid image URLs format | [PR #12](https://github.com/JaswanthKSnjit/homework10/pull/12) | Introduced a regex-based validator to ensure the profile_picture_url ends with .jpg, .jpeg, or .png to confirm a valid image format.

---

## Screenshot Links

- Passes all of [pytest](pytest.png)
- Pytest Coverage is improved to [97%](pytest-coverage.png)
- [swagger UI](swagger-ui.png)
- [Docker Image Deployed](docker.png)

---

## Reflection 

This assignment helped me get a practial knowledge on how collaborative development works on GitHUb. By creatiing separate branches for each issue and trying to solving the issues and the commiting the changes and using pull request and then finally merge working code to the main branch. I learned how we can track our work is easy using GitHub maintaining a clean workflow using version control.

Understanding the FastAPI helped me better improve my backend skills, like creating custome validators for username, passwords and profile image URLs. And also gained much new things when creating the CI/CD pipelines using GitHub actioons and Docker. Writing test cases for pytest and trying to iprove the coverage to 97% really helped me gain extra knowledge on how the test cases works and understood how to write, test and re-write too. 
