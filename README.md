# <div align="center"> Analysise of COVID-19 in India </div>
<p>This project analyse the COVID-19 data (i.e day to day cases and deaths) of India. And it also has a interactive visualization of  day to day COVID cases and deaths. It has visualization which shows the comparision between COVID data like deaths, cases and vaccination.</p>

## Steps to follow
1. Clone the repository to specific folder in your computer.
1. Create Virtual environment in the project folder of the computer.

- #### Windows
  - Firstly, open command prompt window in your project folder.
  - Run `python -m venv example_env` in cmd window. (example_env is the name of the virtual environment. you can replace it with the name you want.)
  - To activate the virtual environment you created, run: `example_env\Scripts\activate.bat`.
  - Now, its time to install the libraries mentioned in the requirements.txt file that are used to build this project. Run `pip install -r requirements.txt`.

3. The data for this project comes from a subset of World Health Organization [WHO](https://covid19.who.int/WHO-COVID-19-global-data.csv) I had take India's COVID-19 data from global csv file, which I had done in excel. So to download that csv file follow this [link](https://drive.google.com/file/d/1EJfVlc98s9-Nd-Gs6YvQj2iMWyWQ6Ukd/view?usp=sharing).
   The Vaccination data comes from the [our world in data](https://ourworldindata.org/) to get the dataset follow this [link](https://github.com/owid/covid-19-data/blob/master/public/data/vaccinations/country_data/India.csv). Or you can download given datasets from this repository.
4. To run an interactive visualization correctly please follow all given steps and run the `MainProjectFile.ipynb` on your machine.
5. Run the `MainProjectFile.ipynb` file on your virtual environment.


**Note:** Install only those versions of libraries on your virtual environment, which I have mention in `requirements.txt` file (to install correct versions, please follow above steps). 







