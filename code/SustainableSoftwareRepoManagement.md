# Sustainable Software Repository Management Policy


## 1 Introduction
This policy describes the software repository management technique that Toasted Marshmallow (Pty) Ltd expects it's employees to abide by when developing software for the company. The policy is open-source as we hope other companies will benefit from our techniques of developing software.

---


## 2 Policy Objectives
The policy exists to achieve the following objectives:

1. Maximize the productivity of the team;

2. Allow any team member to be deployed to any project;

3. Ensure quick feature deployment 

---


## 3 Developer Objectives
As the developer, these are your goals:

1. Merge your recently completed feature code into the _/develop_ branch without experiencing billions of merge conflicts

2. Start on any urgent task, using any of the repo(s) in the company

---


## 4 Team Mentality
For anyone to take on any task in the team it requires that the developers adopt an agile mindset. It is the responsibility of every developer to keep in mind assisting other developers in the team and being "agile" in delivering features. The intention behind this is to firstly deliver features as quickly as possible to address upcoming business needs or bug fixes. Secondly it is to allow our team to work on code that is already running some of the upcoming features. This gives us an opportunity to uncover some bugs in development before they hit production. 

### 4-1 Responsibilities of the Developer
To achieve this the developer needs to be accountable for the following:

1. Understand the [gitflow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow) workflow.

2. Merging semi-stable code into _/develop_ as often as possible 
    
3. Always Pulling the latest version of _/develop_ before beginning a new _/feature_ or _/hotfix_ branch

4. Working within a contained set of files relative to the feature you are addressing

5. Write unit tests to test your code if possible. This is so that other developers don't break your code in future with their changes. 

5. Using concise descriptive names for any _/feature_ or _/hotfix_ branches

6. Merging via pull-requests

---


## 5 Anyone Works on Anything
The idea behind "anyone working on anything" is that the team can then be deployed as necessary to solve the most urgent business problem. In developing software for various customers this is critical for smooth business operation. This effectively will already be occurring if the developers are successfully managing the responsibilities mentioned in Section 4-1. 

### 5-1 Expectation of the _/develop_ Branch
If everyone is abiding by these policies the _/develop_ branch will have the following traits:

1. Be quite recent

2. Compile without issues

3. Run without issues

4. Pass all unit tests

5. Run in a semi-stable fashion

This should always be the case because all the developers in the team will be merging in small and somewhat stable feature branches. Obviously the feature branches should be as stable as possible and unit tested (if possible). But there may be bugs that occur due to other aspects of code that have not been accounted for. These can easily be accounted for with small _/hotfix_ branches.

It's also incredibly important that the code on the _/develop_ branch compiles and runs. This allows any new team member to begin working on a feature immediately.

---


## 6 Branching Strategies

### 6-1 Branching Techniques

#### 6-1-2 Gitflow

#### 6-1-2 Gitflow with Site Deployment

### 6-2 Branch Categories Explained

#### 6-2-1 _/master_

#### 6-2-2 _/develop_

#### 6-2-3 _/feature/something_

#### 6-2-4 _/hotfix/issue-0001_

#### 6-2-5 _/site-deployment/site-name_

### 6-3 Starting a Task

#### 6-3-1 Breaking Down the Task

#### 6-3-2 Branch Naming Convention

#### 6-3-3 Confined File Scope

### 6-4 Working on a Task

#### 6-4-1 Loosely Coupled Code

#### 6-4-2 Unit Tests

### 6-5 Merging Code

#### 6-5-1 Pull Requests

#### 6-5-2 Running Unit Tests

#### 6-5-3 Working with Multiple Projects

---


## 7 Additional Expectations

### 7-1 How Often to Merge
### 7-2 Changes affecting many files
#### 7-2-1 Code Cleanups
