# Microservices and API Security for Security Architects: From Gateway Protection to Container Security
This is the repository for the LinkedIn Learning course `Microservices and API Security for Security Architects: From Gateway Protection to Container Security`. The full course is available from [LinkedIn Learning][lil-course-url].

![course-name-alt-text][lil-thumbnail-url] 

_See the readme file in the main branch for updated instructions and information._
## Instructions
This repository has branches for each of the videos in the course. You can use the branch pop up menu in github to switch to a specific branch and take a look at the course at that stage, or you can add `/tree/BRANCH_NAME` to the URL to go to the branch you want to access.

## Branches
The branches are structured to correspond to the videos in the course. The naming convention is `CHAPTER#_MOVIE#`. As an example, the branch named `02_03` corresponds to the second chapter and the third video in that chapter. 
Some branches will have a beginning and an end state. These are marked with the letters `b` for "beginning" and `e` for "end". The `b` branch contains the code as it is at the beginning of the movie. The `e` branch contains the code as it is at the end of the movie. The `main` branch holds the final state of the code when in the course.

When switching from one exercise files branch to the next after making changes to the files, you may get a message like this:

    error: Your local changes to the following files would be overwritten by checkout:        [files]
    Please commit your changes or stash them before you switch branches.
    Aborting

To resolve this issue:
	
    Add changes to git using this command: git add .
	Commit changes using this command: git commit -m "some message"

## Prerequisites and Setup
1. **Required Tools**: Before starting, ensure you have these tools installed and configured:
	- **kubectl** - Kubernetes command-line tool for cluster management
    - **helm** - Kubernetes package manager for installing applications
    - **istioctl** - Istio service mesh command-line tool
The course demos are optimized for **GitHub Codespaces**, which provides a pre-configured environment with tools like bash and az cli already installed.

2. **Kubernetes Cluster**: You'll need access to a running Kubernetes cluster. Depending on where you host your Kubernetes cluster, some adjustments may be needed.

3. **Getting Started**:
   - Clone this repository to your local machine or open it in GitHub Codespaces
   - Navigate to the specific chapter folders (e.g., `3_4 rate limiting/`, `4_4 istio/`, `5_3 kyverno/`) for each demo
   - Follow along with the course demonstration videos.



[0]: # (Replace these placeholder URLs with actual course URLs)

[lil-course-url]: https://www.linkedin.com/learning/
[lil-thumbnail-url]: https://media.licdn.com/dms/image/v2/D4E0DAQG0eDHsyOSqTA/learning-public-crop_675_1200/B4EZVdqqdwHUAY-/0/1741033220778?e=2147483647&v=beta&t=FxUDo6FA8W8CiFROwqfZKL_mzQhYx9loYLfjN-LNjgA

