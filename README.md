# gitlab-autodevops

Templates for GitLab CI/CD

### Template for gitlab-ci.yml

In order to use gitlab-ci.yml template use the following code:

```yaml
include: 'https://raw.githubusercontent.com/PayU/gitlab-autodevops/master/gitlab-ci-template.yml'
```

### Required CI/CD environment variables

`MVN_BUILD_IMAGE` name of image used to build maven project
 
##### References

* [Auto-DevOps.gitlab-ci.yml](https://gitlab.com/gitlab-org/gitlab-ce/blob/master/lib/gitlab/ci/templates/Auto-DevOps.gitlab-ci.yml)
