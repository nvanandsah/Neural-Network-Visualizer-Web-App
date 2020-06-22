# Neural-Network-Visualizer-Web-App
Web based visualization of neural network prediction using keras and streamlit. Developed while taking [coursera](https://www.coursera.org/learn/neural-network-visualizer/home/welcome) course on the same topic 


## Initial setup
1. Clone the repository: `git clone https://github.com/nvanandsah/Neural-Network-Visualizer-Web-App.git`
2. Install virtualenv: `(sudo) pip install virtualenv` (sudo if required).
3. `cd <repository-path>`
4. `virtualenv venv`
5. Activate virtual environment: 
    For mac and linux: `source venv/bin/activate`.
    For windows: `source venv/bin/activate`.
6. Install the python libraries: `pip install -r requirements.txt`

## Running the program
1. Train the model using `python train_model.py`.
2. Start the flask server using `python ml_server.py`.
3. While the flask server is running, in a new terminal activate the virtual environment and run streamlit server using `streamlit run app.py`

## To start working
1. Activate virtual environment: `source venv/bin/activate`
2. `git checkout master`
3. `git pull`
4. Create a new working branch: `git checkout -tb <new-working-branch-name>`.

## To push your changes-
1. Make sure you are in the new branch you created. You can check the current working branch using `git branch`.
2. `git add .`
3. `git commit -m "<commit-message>"`
4. `git push origin <branch-name>`
5. Create a pull request.

### If you ever install a new python library, make sure to run this command
`pip freeze > requirements.txt`
