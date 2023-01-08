# UTS_Intern
 
## Question 
In business or technical terms describe your understanding of continuous integration and continuous delivery (CI/CD)? What are some tools that are used for this and why are they used? 

## My answer
#### Continuous integration (CI)
1. **CI**:
 As one of the practices of agile, it is to avoid the "merge hell" or eliminate the bugs while multiple developers work on the same script which includes numerous. This practice will help the developer to merge code with builds and tests, which ensures the new code’s correctness before merging to the repository. With CI, the developer will work on a shared version control repository rather than work isolation. CI will bring the benefit to project as listed below: 
   * No merge hell
   * Testable build
   * Deliver update faster

1. **Tools & Why**:
   - **Tools**: Bitbucket Pipelines, Jenkins, AWS CodePipeline, CircleCI, Azure Pipelines, GitLab, Atlassian Bamboo. These tools usually contain the function of version control management, automated testing, build automation and automated deployment.
   - **Why**: The tools are used to deploy CI to overcome the difficulty and time-consuming of the changed code merging. The function provided by CI tools will accelerate delivery updates and ensure code quality.

![image](https://user-images.githubusercontent.com/24654508/211180325-b17f861c-5f2d-470a-a05d-c0ca729be66c.png)


#### Continuous Delivery (CD)

 1. **CD**:
   Continuous Delivery is an end-to-end release process that includes automated builds, tests, configuration and deployment, emphasis on integration, testing, monitoring. it forms a comprehensive loop and fast-reaction protocol that cover every step in development including the first release, user feedback, new code and new release.
   CD brings business value to customers with release continually and without errors during development. Which keeps the production environment updated to date while it optimizes the processing time and eliminates idle time.  

 2. **Tools & Why**:
    - **Tools**: Gradle, Jenkins, BuildBot, Buddy, Ant, these tools usually contain development, testing, quality assurance, monitoring and alerting functions.
    - **Why**: CD tools optimize DevOps practice and foster team collaboration. It also enhances the development and release process to overcome the challenges in CD including continuous testing, scripts and security.

#### Reference Link:

1. https://www.atlassian.com/
2. https://aws.amazon.com/devops/
3. https://learn.microsoft.com/en-us/devops/develop/
4. https://www.openxcell.com/blog/continuous-delivery-tools-in-devops/#:~:text=List%20of%20the%20top%205%20continuous%20delivery%20tools,DevOps%20more%20accessible.%20...%205%205.%20Ant%20\
5. https://www.openxcell.com/blog/continuous-delivery-tools-in-devops/#:~:text=List%20of%20the%20top%205%20continuous%20delivery%20tools,DevOps%20more%20accessible.%20...%205%205.%20Ant%20

