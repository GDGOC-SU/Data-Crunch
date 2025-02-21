# Data-Crunch

Welcome to the **Data-Crunch** repository! This is the playground for the Data Crunch event under GDGOC SU. Participants will push their code to this repository in separate branches, with each branch named after their team name.

## How to Push Your Code to This Repository

Follow these steps to push your team's code to the repository in a branch named after your team:

### Prerequisites
1. **Git Installed**: Ensure you have Git installed on your system. If not, download and install it from [here](https://git-scm.com/).
2. **GitHub Account**: Make sure you have a GitHub account and have access to this repository.
3. **Repository Cloned**: Clone this repository to your local machine.

### Steps to Push Your Code

1. **Clone the Repository** (if not already cloned):
   ```bash
   git clone https://github.com/GDGOC-SU/Data-Crunch.git
   cd Data-Crunch 
   ```
2. **Create a New Branch** 
    ```bash
    git checkout -b [teamname]
    ```
    Replace [teamname] with your actual team name (e.g., team-awesome). <br> <br>

3. **Add Your Code**
   Place your code/files in the appropriate directory or create a new folder for your team. <br><br>

4. **Stage Your Changes**
   ```bash
   git add .
   ```

5. **Commit Your Changes**
Write a meaningful commit message describing your changes.

```bash
git commit -m "Added code for [teamname]"
```
6. Push Your Branch to GitHub:
Push your branch to the remote repository.

```bash
git push origin [teamname]
```
7. **Verify Your Branch**
Go to the GitHub repository and check if your branch has been created and your code is uploaded.

Example
If your team name is `team-awesome`, here’s how your commands would look:

```bash
git checkout -b team-awesome
git add .
git commit -m "Added code for team-awesome"
git push origin team-awesome
```
8. **Visuals Submission**
   Participants are also advised to share the screen-shots of their graphs,
maps and other visualization techniques creating a folder in their branch.

## Important Notes
- Do NOT push to the main branch. Always create and push to your team's branch.

- Ensure your branch name is unique and matches your team name exactly.

- If you encounter any issues, reach out to the event organizers for assistance.

## Dataset Information

The dataset for the competition is the **Breast Cancer Wisconsin (Diagnostic) Data Set**. The goal is to predict whether the cancer is benign or malignant. Below are the details:

### About the Dataset

- Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image.  

### Attribute Information

1) ID number  
2) Diagnosis (M = malignant, B = benign)  
3) Ten real-valued features are computed for each cell nucleus:  
   - radius (mean of distances from center to points on the perimeter)  
   - texture (standard deviation of gray-scale values)  
   - perimeter  
   - area  
   - smoothness (local variation in radius lengths)  
   - compactness (perimeter^2 / area - 1.0)  
   - concavity (severity of concave portions of the contour)  
   - concave points (number of concave portions of the contour)  
   - symmetry  
   - fractal dimension ("coastline approximation" - 1)  

- The mean, standard error, and "worst" or largest (mean of the three largest values) of these features were computed for each image, resulting in 30 features.  
- All feature values are recoded with four significant digits.  
- Missing attribute values: none  
- Class distribution: 357 benign, 212 malignant  



## Evaluation Criteria
The evaluation of your submission will be based on the following criteria:

- **Code Quality**: Clean, well-structured, and readable code.

- **Functionality**: Does the code work as intended?

- **Innovation**: Creative and unique approach to solving the problem.

- **Documentation**: Clear and concise documentation of your code and approach.

For detailed` evaluation` and `level` guidelines, download the Evaluation PDF [here](https://drive.google.com/drive/u/0/folders/1d71udIx71MQPo4YPp3lL_cb_yc_J7YGm)

## Need Help?
If you have any questions or face issues, feel free to contact the event organizers or open an issue in this repository.

## Happy Coding!
*Organized by GDGOC SU 
Event: Data Crunch
Repository: Data-Crunch*