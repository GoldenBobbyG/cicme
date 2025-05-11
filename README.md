## Title
CIme

## Installation 
**Clone the repository:**

git clone https://github.com/GoldenBobbyG/cicme.git
cd cicme

##🧪 Usage
Branching Strategy
Feature development: Create a new branch off develop.

Code review: Submit a pull request into develop.

Production release: Merge develop into main to trigger deployment.

GitHub Actions Workflow
Event	Action
Pull request to develop	Run Cypress component tests via CI
Merge into main	Auto-deploy to Render using CD pipeline

Testing with Cypress
Tests run automatically on GitHub when you push a PR to develop.

View test results in the Actions tab of the GitHub repository.

Deployment
The app is automatically deployed to Render when changes are pushed to main.

Ensure your Render service is connected to this GitHub repo.


## Deploy Link 

https://cicme.onrender.com

## License 
 MIT License 

 ## Notes 
 used copilot and zoom recordings 


## Questions
For any questions, please contact me at stricklandmba2011@gmail.com. You can also find more of my work at GoldenBobbyG.
