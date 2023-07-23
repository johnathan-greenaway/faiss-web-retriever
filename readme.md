#######################################
#   MPCVS: Web Ingestion & Q&A AI     #
#   Version: 1.0.0                    #
#######################################

# #####################################
# ########## Dependencies #############
# #####################################
# 
# The dependencies can be installed by running:
# `pip install -r requirements.txt` in the root directory of the project.
# Below are the necessary packages:
# 
# requests==2.26.0
# openai==0.27.0
# numpy==1.21.2
# beautifulsoup4==4.9.3
# scikit-learn==0.24.2
# streamlit==0.88.0
# 
# #####################################
# ########## Setup & Deploy ###########
# #####################################
# 
# 1. Clone the repository:
#     `git clone https://github.com/wazacraft/mpcvs.git`
# 
# 2. Change to the project directory:
#     `cd mpcvs`
# 
# 3. Create a python virtual environment named mpcvs:
#     `python3 -m venv mpcvs`
# 
# 4. Activate the virtual environment:
#     - On Windows: `mpcvs\Scripts\activate`
#     - On Unix or MacOS: `source mpcvs/bin/activate`
# 
# 5. Install the dependencies:
#     `pip install -r requirements.txt`
# 
# 6. Set up OpenAI API key:
#     Add the OpenAI API key to your environment variables. 
#     The method depends on your operating system and shell, 
#     but one common approach is adding `export OPENAI_API_KEY='your-api-key'` 
#     to your `.bashrc` or `.bash_profile` and then source it.
# 
# 7. Run the application:
#     `streamlit run launch.py`
#     and then 
#     `python launch.py`
# 
# #####################################
# ####### Usage Instructions ##########
# #####################################
# 
# 1. Ingestion:
#     - Enter URLs to scrape in the 'Enter URLs to scrape/ingest' text area.
#     - Click the 'Ingest' button. The application will scrape each web page, 
#       create embeddings for the content, and store the results.
# 
# 2. Question and Answer:
#     - Enter your question in the 'Enter a question to ask OpenAI API based on ingested data' text input.
#     - The application will generate a response using the most similar text chunk from the ingested data.
# 
# #####################################
# ######### Release Notes #############
# #####################################
# 
# Version 1.0.0:
# - Data Ingestion: The application can ingest data from web URLs.
# - Q&A: The application can answer questions based on the ingested data using OpenAI's GPT-4 model.
# 
# #####################################
