
# Preprint fetcher 


#### This code should be locally run on your computer 

<br>

  ### Setup:
  
  1. Download the scripts from onto your local machine 
  
  2. Go into the folder
     
     ```
     cd biorxiv_shareable
     ```
  
  4. Create a virtual environment

      ```
      python3 -m venv .venv
      source .venv/bin/activate
      ```
  
  6. Install the one dependency
  
      ```
      pip install requests
      ```
  
  4. Create a personal config - open config.json and fill in your keywords and authors
  
      ```
      cp config.example.json config.json
      ```
  
  5. Test 
      ```
      python biorxiv_fetcher.py
      ```
  
  6. Install the daily scheduler
  
      ```
      python scheduler.py --install-launchd
      ```
<br>

#### Scripts written with the assistance of Claude, Sonnet 4.6
