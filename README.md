# pfSharedLibraryLoader

OSS Jenkins shared library to dynamically load other shared libraries from GitHub repositories.

## Usage in Jenkinsfile

```groovy
pfSharedLibraryLoader(
    repo: "pxfd/Devops.Infra.tf-apps",
    path: "resources/containers/buildx.yaml",
    branch: "main",
    credentials: "jenkins-github-token"
)
