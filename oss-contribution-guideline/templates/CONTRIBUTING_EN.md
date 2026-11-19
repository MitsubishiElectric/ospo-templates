<!--このCONTRIBUTINGはテンプレートです。プロジェクトに合わせて適宜修正してください。-->
# Introduction
<!--冒頭の挨拶を記載します。[任意]-->
First of all, thank you for your contributions!
Please contribute to the project by following the guidelines below.

## Types of Contributions
<!--プロジェクトがどのような種類のコントリビューションを求めているのかを記載します。[推奨]-->
This project accepts the following types of contributions:
1. **Bug Reports**:  
If you find a bug, please create an issue to report it. Please provide as much detail as possible, including steps to reproduce the issue and any relevant screenshots.
2. **Feature Requests**:  
If you have an idea for a new feature, please create an issue to discuss it. Please explain the details of the feature and its usefulness.
3. **Code Contributions**:  
If you’d like to contribute code, please follow the steps below.
4. **Documentation**:  
Improving the documentation is also a valuable contribution. This includes updating existing documentation, adding new documentation, or correcting typos.
5. **Testing**:  
You can contribute by testing the project and reporting any issues you find. Writing tests for the codebase is also a form of contribution.
6. **Vulnerability Reporting**:  
If you discover a vulnerability, please report it to the mailing list (foo@bar) rather than via an issue or pull request, for security reasons.

## Contribution Workflow
<!--コントリビューションの流れを記載します。[必須]-->
1. **Check for or Create an Issue**:  
Check the existing issues to see if the same problem or suggestion has already been raised. If not, create a new issue and provide as much detail as possible.
2. **Fork the Repository**:  
Fork the repository to your GitHub account and clone it to your local environment.
3. **Create a Branch**:  
Create a new branch for your work. Choose a descriptive name for the branch.
    ```bash
    git checkout -b feature/new-feature-name
    ```
4. **Make Changes**:  
Make changes on the new branch. Ensure your code follows the project’s coding standards.
5. **Commit changes**:  
Commit your changes with a meaningful commit message.
    ```bash
    git commit -s -m “Add New Feature Name”
    ```
   Adding `-s` automatically inserts the `Signed-off-by:` line required for the Developer Certificate of Origin (DCO), which will be covered later.  
6. **Push the changes**:  
Push the changes to your fork of the repository.
    ```bash
    git push origin feature/NewFeatureName
    ```  
7. **Create a pull request**:  
Create a pull request on GitHub against the original repository. Clearly describe the changes and link to any related issues.

## Developer Certificate of Origin (DCO)
<!--DCOを利用する場合に記載します。[推奨]-->
This project uses the [Developer Certificate of Origin (DCO)](https://developercertificate.org/). The DCO is a mechanism for confirming that contributors “have the right to submit their contributions” and that they “are submitting them under the terms of this project’s license.”  
1. **Agreeing to the DCO**  
If you contribute to this project via commits, pull requests, patches, or any other means, you are deemed to have agreed to the DCO.

2. **Adding a `Signed-off-by` Line**  
Please include a `Signed-off-by:` line in all commits.
  ```bash
　　Signed-off-by: Name <email address>
  ```
　　　Example: Signed-off-by: Taro Yamada <taro@example.com>

3. **How to Add It**  
You can automatically add the `Signed-off-by:` line using the following command:
  ```bash
　　git commit -s
  ```
　　　　Or
  ```bash
　　git commit --signoff
  ```
4. **Commits Included in a PR**  
All commits included in a Pull Request must include a `Signed-off-by:` line.
If you add or modify a commit, please verify that it has been signed off again.

5. **Important Notes**  
    - When using code or text written by others, verify the appropriate rights and permissions.
    - For collaborative works, obtain the consent of the co-authors as necessary.
    - If the work was created as part of your duties for a company or organization, verify that you have the authority to submit it.
    - The “Signed-off-by:” line does not imply a transfer of copyright.

## Issue and Pull Request Guidelines
<!--Issueとプルリクエストのガイドラインを記載します。[推奨]-->
- **Issue**: Please provide as much detail as possible when reporting bugs or suggesting features. It would be helpful to include steps to reproduce the issue and screenshots.
- **Pull Request**: When creating a pull request, please link to the relevant issue number and briefly describe the changes.

## Communication
<!--コミュニケーションをとるための方法を記載します。[必須]-->
- Please use the “Issues” or “Discussions” tabs for questions and discussions.
- We strive to respond promptly, but please note that it may take some time to respond to your inquiry. Thank you for your understanding.
