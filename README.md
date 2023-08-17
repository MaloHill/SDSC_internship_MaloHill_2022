# SDSC_internship_2022
Code and report from the internship "Statistical methods for comparing mass spectra".

Information about the internship can be found in the report, which is in the "report and slides" file together with slides used during presentations.

Experiments, graphics and implementation contain the code in the form of Jupyter notebooks.

Data contains the initial csv files of the spectrum database and additional files produced by the code and useful for running the code.

The folder ll_files contains data which was not in the initial database, but was created from by the program in "Dirichlet-multinomial_v4", so that each time I wanted to continue to work on this program, I only had to load the csv files containing the previous results instead of computing the results all over again. However, some of these csv files are too heavy to be uploaded in the git repository. These can be recovered by running the program "Dirichlet-multinomial_v4.

Note: the directories of the csv files need to be fixed in the code before making it run (look for where the string of characters data_dir and sub_directory are defined and replace them with the directory that works for you).
