#Amazon Product Data Reporter

This python script grabs the details of all the items (from first page) of a particular product and stores in a file in json format.
It grabs product ID, title, price, url, and seller.
```
Note: This tracker specfically designed for amazon.in so, may or may not work for other urls
```
##Usage
```
python -m venv myenv
source myenv/bin/activate
pip install -r requirements.txt

python tracker.py
```

You can change the searched item and price filter in amazon_config.py file to search for the according to your requirement.

You can remove comment in the set_headless() method in the tracker.py file method to make the browser headless i.e the browser will run internally.
