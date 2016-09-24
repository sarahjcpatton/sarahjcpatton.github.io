# sarahjcpatton.gitlab.io

Plain HTML website with static files.

### Status

![Build Status](https://gitlab.com/pages/plain-html/badges/master/build.svg)

### Notes

- [EDIT FILES HERE](public)
- [Web Editor Documentation](https://docs.gitlab.com/ce/user/project/repository/web_editor.html)

### GitLab CI

This project's static Pages are built by
[GitLab CI](https://about.gitlab.com/gitlab-ci/), following the steps defined
in [`.gitlab-ci.yml`](.gitlab-ci.yml):

```
pages:
  stage: deploy
  script:
  - echo 'Nothing to do...'
  artifacts:
    paths:
    - public
  only:
  - master
```
