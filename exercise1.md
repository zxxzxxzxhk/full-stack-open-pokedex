Question 1: CI setup has five core steps including Lint, Build, Test, Package, and Deploy. Specific tools are provided for taking care of these steps in the real world.

The specific tools for these steps are listed below :

1. Lint: GitLab CI Lint tool, ESLint, Prettier.
2. Build: GitHub Actions, Gradle, Bazel
3. Test: Playwrite, Cypress
4. Package: Webpack
5. Deploy: Travis CI

Question 2: Besides Jenkins and GitHub Actions, we can use CircleCI, Azure DevOps, Travis CI, etc. to set up CI

Question 3 : Cloud-based environment is a better setup. There are several reasons. 
First, using a cloud-based environment does not require self-maintained hardware or software infrastructure as our team is small and does not have enough manpower to build and maintain an own test environment. 
Also, the setup process of a cloud-based environment is easier and faster because the preparation of host server is not needed which is set by the service provider. 
Furthermore, the test environment can be scaled easily due to the flexibility of deploying additional cloud infrastructure. 
On the other hand, cloud-based CI/CD tools are easy to use. They can simplify and streamline our software development and delivery process, by providing easy-to-use interfaces, templates, workflows, and automation capabilities.
Last but not least, it offers better flexibility, we can choose different vendors or platforms in order to fit our application.