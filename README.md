# Suggestions/Comments for Rachel and Melanie:

- Overall, the notebooks are really easy to understand and well-written code wise
- Some of the only suggestions that I have would be to create a `README.md` file right when you open the repository (similar to the file that I'm writing in right now) that easily outlines what each and every notebook file does so that if you in the future or any other person wants to re-run your code a year from now, they know exactly where to start and what to expect.
  - An example of this could be seen below in the next section
- Additionally, I would try to organize the repository in a bit of a nicer way lets say. Rather than having some original .csv files in `UK Education provision under 5s` and some others scattered around the repository, I would have a subfolder called `original_data` where each of these original data files would live and also have another subfolder called `output_files` where the new data files would theoretically be written to. Also, when it comes to the data, always try to remember to put a link to where these files came from, which you can do within another `README.md` file ***within** *the `original_data` subfolder
  - Proposed structure:
    - group_project_m_r
      - notebooks/
        - ....ipynb
        - ....ipynb
        - ....ipynb
      - original_data/
        - original_file1.csv
        - original_file2.csv
        - original_file3.csv
        - README.md <- this should contain links to where the data files came from
      - output_files/
        - output_file1.csv
        - output_file2.csv
        - output_file3.csv
      - README.md

# Example: Explanation of Notebooks

This repository contains the following notebooks:

- `disadvantage_process_for_join.ipynb`: This notebook does X, Y, and Z specifically by utilizing the original A, B and C datasets. As an output, this notebook creates the X csv file.
- `joined_15_hours.ipynb`: This notebook does X, Y, and Z specifically by utilizing the original A, B and C datasets. As an output, this notebook creates the X csv file. This created X file is needed as input into another notebook called `XYZ.ipynb`
