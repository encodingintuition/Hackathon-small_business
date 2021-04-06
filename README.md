# Small Business Hackathon 
<hr/>
 

Team : Hidden Gem  
UX:  [Nandinis Gupta](https://www.linkedin.com/in/nandinisgupta) ,  [Sari Beall](https://www.linkedin.com/in/sari-beall/) , and [Natallia Berakchyian](https://www.linkedin.com/in/natalliaberakchyian/)  
SE: [Evandro Rodrigues](https://www.linkedin.com/in/evandro-jr-rodrigues/), [Alexander Bos](https://www.linkedin.com/in/alexander-bos/), and [Zander Horstman](https://www.linkedin.com/in/zanderhorstman/)  
DS: [Christopher Villafuerte](https://www.linkedin.com/in/christophervillafuerte/)
<br>

### Concept:

Hidden Gem is a listing site dedicated to small business Bed and Breakfasts. In addition to a listing site that caters to Bed & Breakfast patrons' nuances, Hidden Gem contains a catalog of unique attractions that local business owners have entered.  These attractions can range from local hikes, waterfalls, magical antique stores, excellent restaurants, and such like; these attractions are the Hidden Gems.  The majority of the Gems are not viewable from the website and show up as blurred images.  Once the guest books the Bed & Breakfast, all of the local Gems related that Bed & Breakfast can be viewed.   The local Gems allow the guest to immerse themselves within a new environment from a local perspective. 

# Contents:  
- [API](#GeoSpatial-API)  
    - Filters locations based on proximity to a binding venue using GIS data.
    - geo_sort-key_bnb.py
- [Questionaire Analytics](#Questionaire-Analytics)
    - Descriptive Analytics from the questionnaire, including NLP analysis, word segmentation and sentiment analyzer.
    <br>

#### Contributions:
  - Concept Brain storming   
  - Team Communication   
  - GeoSpatial Maniplation API 
  - Questionaire Analitics   

# GeoSpatial API
<hr/>

**API** *function*
- New Local Gems will be added by Bed & Breakfast owners (Through a process, guests will also be able to add Local Gems )
- Once a guest books their stay, the API will sort through all the Gems using their geopositioning coordinates and select the Gems within a particular radius $(r_i)$ of the chosen Bed & Breakfast.  
- This list of local Gems is returned to the Hidden Gem backend, creating a viewable linked page for the Local Gems.


**Versions:**  
- v1: API is passed Bed & Breakfast keys via , data is hard coded  
- v2: API is passed Json file incudes all GIS data  
- v3: API is passed Bed & Breakfast Keys via, and pulls Gems GIS data from SQL DataBase  

# Questionaire Analytics
<hr/>


```python

```
