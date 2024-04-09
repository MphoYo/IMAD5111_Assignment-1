# IMAD5111_Assignment-1
My history app
Introduction

The History App is a novel platform designed to connect users with historical figures through age comparison. By inputting their age, users can explore which famous figures that died during the same age range. This comprehensive report examines the purpose of the History App, its design considerations, and the strategic use of GitHub and GitHub Actions in its development.

•Purpose of the History App

The primary goal of the History App is to make history more accessible and engaging by personalizing the learning experience. It aims to achieve the following objectives:
Engagement: The app seeks to captivate users by offering a unique and interactive way to interact with historical content. By comparing their ages to famous figures, users are encouraged to explore and learn about different periods of history.
- Education: Through age comparison, the History App serves as an educational tool, fostering curiosity and understanding of historical events and figures. It aims to inspire users to delve deeper into historical topics and gain a broader perspective on the past.
- Connection: By establishing a personal connection between users and historical figures, the app aims to humanize history and make it more relatable. Users can see themselves within the context of history, enhancing their sense of connection to the past.
- Relevance: The History App strives to demonstrate the relevance of history to modern life. By highlighting the achievements and experiences of historical figures, it encourages users to reflect on how the past has shaped the present and consider its implications for the future.

•Design Considerations

The design of the History App is guided by several key considerations to ensure an intuitive and engaging user experience:
- User Interface (UI): The UI is designed to be visually appealing and easy to navigate, with intuitive controls and clear feedback mechanisms. Emphasis is placed on simplicity and accessibility to cater to users of all ages and backgrounds.
- Age Comparison Algorithm: A robust algorithm is implemented to accurately calculate age comparisons between users and historical figures. 

- Database of Historical Figures: The app incorporates a comprehensive database of historical figures spanning various time periods and cultures. This allows for a wide range of comparisons and ensures inclusivity and representation across different historical contexts.
-Error Handling: we ensure that app handles input errors, providing constructive feedback to the student if they put age above 100, also the users will only able to put age as whole numbers. We limit the age between 20 years old and 100 years old. 
-Easy navigation
This means ensuring that any new screens or pages are accessible via a single click or tap on the net. This is important because it makes things easier for users, and helps prevent navigation errors by eliminating confusion about where they should go next (i.e., if you have two tabs open at once).
-Clear labelling
The most important thing to remember when working on any design is that your users will look at it all day long. That means they need a way to navigate your app and easily find the information they want.
- Accessibility: Accessibility features are prioritized to ensure that the app is usable by individuals with diverse needs and abilities. Options for adjusting font sizes, colour contrast, and screen reader compatibility are provided to enhance accessibility for all users.
- Mobile Compatibility: The app is designed to be responsive and compatible with a range of devices, including smartphones and tablets. This ensures that users can access the app anytime, anywhere, and on any device, enhancing its accessibility and usability.
•Utilization of GitHub and GitHub Actions
GitHub and GitHub Actions play a crucial role in the development and maintenance of the History App:
- Version Control: GitHub serves as a centralized repository for the app's source code, enabling collaboration among developers and ensuring version control. This allows for efficient management of code changes and facilitates transparency and accountability within the development team.
- Issue Tracking: GitHub's issue tracking system is used to manage and prioritize tasks, track bugs, and gather feedback from users and contributors. This helps to streamline the development process and ensure that issues are addressed in a timely manner.
- Continuous Integration and Deployment (CI/CD): GitHub Actions automates the CI/CD pipeline, allowing for seamless integration, testing, and deployment of code changes. Automated workflows ensure consistency and reliability in the development process, enabling rapid iteration and deployment of new features and updates.
-An action is a custom application for the GitHub Actions platform that performs a complex but frequently repeated task. Use an action to help reduce the amount of repetitive code that you write in your workflow files. An action can pull your git repository from GitHub, set up the correct toolchain for your build environment, or set up the authentication to your cloud provider.
-A job is a set of steps in a workflow that is executed on the same runner. Each step is either a shell script that will be executed, or an action that will be run. Steps are executed in order and are dependent on each other. Since each step is executed on the same runner, you can share data from one step to another. For example, you can have a step that builds your application followed by a step that tests the application that was built.

You can configure a job's dependencies with other jobs; by default, jobs have no dependencies and run in parallel with each other. When a job takes a dependency on another job, it will wait for the dependent job to complete before it can run. For example, you may have multiple build jobs for different architectures that have no dependencies, and a packaging job that is dependent on those jobs. The build jobs will run in parallel, and when they have all completed successfully, the packaging job will run.
You can write your own actions, or you can find actions to use in your workflows in the GitHub Marketplace.
- Collaboration and Documentation: GitHub provides tools for collaboration and documentation, including wikis, project boards, and pull request reviews. These features facilitate communication and knowledge sharing among team members, fostering a collaborative and productive development environment.
-You can configure a GitHub Actions workflow to be triggered when an event occurs in your repository, such as a pull request being opened or an issue being created. Your workflow contains one or more jobs which can run in sequential order or in parallel. Each job will run inside its own virtual machine runner, or inside a container, and has one or more steps that either run a script that you define or run an action, which is a reusable extension that can simplify your workflow.
- Community Engagement: GitHub fosters community engagement by enabling contributions from external developers through pull requests, issue discussions, and code reviews. This open-source approach encourages collaboration and innovation, enriching the app's features and functionality.

•Conclusion
In conclusion, the History App represents a pioneering effort to make history more accessible, engaging, and relevant to users through age comparison. By leveraging intuitive design principles and utilizing GitHub and GitHub Actions for development, the app offers a seamless and enriching user experience while fostering collaboration, innovation, and community engagement. With its emphasis on education, connection, and relevance, the History App stands as a testament to the transformative power of technology in enhancing historical understanding and appreciation in the digital age.
Reference
https://elearningindustry.com/top-elements-every-successful-business-application-design-must-have
https://appitventures.com/blog/interesting-facts-and-history-about-android-app-development



https://youtu.be/zswQmsWYiSw
