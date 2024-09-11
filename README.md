# SRA Software Department Recruitment Lab 2024

Welcome to the **SRA Software Department Recruitment Lab 2024**! This repository is designed to evaluate your learning ability. Please note that we are not testing your programming skills, so relax and focus on the tasks at hand.

We will be judging you based on various aspects throughout this activity. If you encounter issues, please take note of how you resolve them. You can also ask your team members in the group chat for help. Your ability to communicate effectively and assist others will be considered as part of the evaluation process for your application.

## Requirements

Before you begin the lab, please ensure you have the following set up:

- **Git**: Ensure that Git is installed and properly configured on your computer. This means you should have your user information (such as your email and name) set up.
   > tutorial references:  [git and github, en](https://www.youtube.com/watch?v=hrTQipWp6co)
   or [一小时git教程, zh-CN](https://www.bilibili.com/video/BV1HM411377j/?spm_id_from=333.337.search-card.all.click). 
- **GitHub Account**: You will need a GitHub account to participate in this lab. If you don’t have one, please create it [here](https://github.com/join).
- **Technical Stack**: Make sure you have the necessary tools and software installed on your computer. 
- **Any IDE or Code Editor**: You can choose any code editor if you like, we would recommend you to use vscode, it is open source and light weight.
- Knowledge of Basic Shell Commands and Markdown: Familiarity with basic shell commands and Markdown (MD) syntax is required.
   > tutorial references:    
   [30分钟Shell光速入门教程, zh-CN](https://www.bilibili.com/video/BV17m411U7cC/?spm_id_from=333.337.search-card.all.click).   
   关于 MD 语法，问 [gpt](https://chatgpt.com/) 就行。多写多看，也就会了，没必要专门去学，看教程。


## Instructions

If you have previously contributed to any open source community or worked on side projects, and you are applying for an coder position, you can bypass some of the lab tasks.

### Administor and Project leader
1. **Create a Markdown File**: Create a `your-repo-name.md` file in this repository.
2. **Link Your Repository**: In the Markdown file, provide links to your repository.
3. **Find Your Project Member**: You should ensure that others can deploy your project locally and make modifications based on it. To facilitate this, provide a brief tutorial on how to work with your project. Additionally, you need to find someone to deploy your project. This involves persuading them to use your project, assisting them with any issues they encounter, and tracking their progress.

### Coder
1. **Fork this lab repo**:  
   - You have to fork this lab repo
   - Clone from your forked repo to your local, and remember, you have to push the final work(lab) to this remote.

1. **Create your own `git branch`**:
  - Before you start your code journey. In the project root directory (`path-to-your-project/`), you justed cloned it from step 1, create a new branch called(`position/your-name` like `coder/rupert`)

3. **Create a Directory Called `projects`(alternative)**:  
   Create a folder named `projects` in the main directory of this repository if you want to clone more than a single project. Then, you can clone different projects into this folder. If you just want to clone one project and make modifications, you are suggested to directly add your `your-repo-name.md`.

     ```
     .
     ├── README.md
     └── projects
         ├── react-documentations-website.md
         ├── wku-sra-wiki.md
         └── ...
     
      
     ```

      ```
      .
      ├── README.md
      └── react-documentations-website.md
      
      ```

4. **Find and Clone an Open Source Project**:
  - Choose an open-source project from the following options, as they are generally easier to deploy than other projects, assuming you have prior programming knowledge. If you prefer, you can deploy any project of your choice, or select your own project if you are applying for a project leader or administrator position:
     - [React Documentation Website](https://github.com/reactjs/react.dev)
     - [Flutter Documentation Website](https://github.com/flutter/website)
   - Fork the project to your [own repo](https://github.com/WKU-SRA-Dev/website) like this one we show you.
   - Clone the chosen project **FROM YOUR OWN REPO** into your local, and you will develop based on that repo, you are recommended to use another directory to clone this repo, because that will keep your git repo clear.  
   If you are in the lab directory, with the previous example:
   
   ```bash
   cd ..
   git clone git@github.com:WKU-SRA-Dev/website.git
   ```
   
   This maybe our lab repo:
   ```
   ~/sra-recruitment-lab
   ```
   This maybe the repo you cloned:   
   ```
   ~/website
   ```
   bonus: ~ represent the home directory of the current user. 

You can find instructions on how to deploy the project locally in the respective repositories.


5. **Make Changes Based on the Project You Cloned**:
   - Modify the cloned project to demonstrate your ability to quickly understand and work with an unfamiliar codebase.
   - Capture screenshots of your changes.
   - Return to the lab project
   - Summarize what you did and what you learn in the `*.md` file
   - Save these screenshots in a separate folder named `img` within the root directory of this repository. The folder structure should look like this:
     ```
     .
     ├── README.md
     ├── projects
     │   ├── react-documentations-website.md
     │   ├── wku-sra-wiki.md
     │   └── ...
     │
     └── img
         ├── change-the-home-page.png
         ├── others.png
         └── ...
     ```
     or
      ```
      .
      ├── README.md
      ├── react-documentations-website.md
      └── img
          ├── change-the-home-page.png
          ├── others.png
          └── ...
      ```

6. **Submit Your Changes To Your Forked Repo**:  
   - Commit your changes to your forked repository(you cloned as the project you are developing, **not the lab** (`path-to-your-cloned-repo/`).
   - push your commits to your own remote repo (the forked repo)    

   >You should have a clear description of what you did in your commit message. The commit message will show your commit time, so keep learning during the labs. Do not try to finish within 2 hours : )

   ![commit](img/commit1.png)
   
7. **Submit this lab when you finish all the jobs**:
  - Return to the lab   
  - ENSURE YOU ARE ON YOUR OWN BRANCH like `coder/rupert`
  - commit all your changes 
  - push to your forked lab repo（not the repo you cloned and developed）
  - Pull a request (pr) to our lab repo


### Bonus Section

The above tasks are intended to assess your ability to learn unfamiliar topics, particularly in situations where you may have no prior experience in programming. The following are additional bonus tasks. While they are not the primary criteria for our selection process, excellent works in these tasks can set you apart from your peers in a competitive environment.











