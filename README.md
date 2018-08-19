# Linx Data Science Challenge

My results for the Linx Impulse Data Science challenge, offered for the job placement in Data Science during the Work Week event.

# Tools and environment used

For this challenge, I used a docker container, Jupyter notebook and the 'pandas' and 'matplotlib' libraries. However, all the components contained in the container used are specified in the 'requirements,txt' document.

**Assuming you have docker installed, run the commands below:**

git clone  git@github.com:wcamposs/linx-data-science-challenge.git

cd linx-data-science-challenge

docker-compose up

and access Jupyter in your browser on: http://localhost:8888


# Tests

In order to avoid any unexpected errors during document correction, each question of challenge was executed in a unique way.

Finally, the whole script was executed to ensure that no script execution error appears during the document correction.

# Dataset Used

The Dataset used for this challenge was downloaded from his link: https://s3.amazonaws.com/ml-challenge/ecommerce-events.ndjson.xz
20M compressed, 300M uncompressed.

The documentation for this dataset is summarized in dict format in the file 'dataset_documentation.ipnb'.

# Documents contained
1. **notebook**                           # Directory with the challenge and documentation
  1. **data_science_challenge.ipnb**      # Codes and results for the challenge
  1. **dataset_documentation.ipnb**       # Documentation of the dataset used
2. **requirements.txt**                   # Requirements used on the Docker Container
3. **Dockerfile**                         # Docker definition file
4. **docker-compose.yml**                 # Compose file defining services

# Credits

Credits to Linx Impulse for providing the dataset used during the challenge 
