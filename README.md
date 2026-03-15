
# Preprint fetcher 


#### This code should be locally run on your computer 

<br>

  ### Setup:
  
  1. Download the scripts onto your local machine 
  
  2. Go into the folder
     
     ```
     cd preprint_fetcher
     ```
  
  3. Create a virtual environment

      ```
      python3 -m venv .venv
      source .venv/bin/activate
      ```
  
  4. Install the one dependency
  
      ```
      pip install requests
      ```
  
  5. Create a personal config - open config.json and fill in your keywords and authors
  
      ```
      cp config.example.json config.json
      ```
  
  6. Test 
      ```
      python biorxiv_fetcher.py
      ```
  
  7. Install the daily scheduler
  
      ```
      python scheduler.py --install-launchd
      ```
      
  8. Open the output file from the “feed_output” subfolder, view feed in broswer, and optionally bookmark
     
<br>

#### Scripts written with the assistance of Claude, Sonnet 4.6
