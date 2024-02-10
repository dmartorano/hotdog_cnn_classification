# *Hot dog* or *Not hot dog*

Your data team has decided to move outside of the consultation business and into creating its own app! After months of brainstorming and market research you finally identify a gap in the market. You pitch the idea for the app "SeeFood". It's Shazam for food. You get funded immediately. Time to get to work!

* Group 1: Aaran, Daniel K, Heather
* Group 2: Ben M, Dom, Steve
* Group 3: Ben W, Danny C, Kelly

## Deliverables

* A prototype Streamlit app where a user can upload a picture. Your app will display whether a Hot Dog is present or not. 
* Updated README that includes:
  * team info & contributions
  * requirements (python environment & libraries required)
  * summary of modeling process
  * model evaluation & chosen model
  * link to your app

## Data 
[This link will direct you to your data](https://www.kaggle.com/yashvrdnjain/hotdognothotdog#__sid=js0).

## Suggested Timing / Milestones (Eastern time)
* **9 AM - 10.30 AM**: data acquisition, documentation & methodology
* **10.30 AM - 12 PM**: initial modeling
* **1 PM - 3 PM**: model evaluation & refinement
* **3 PM - 4 PM**: pickling & app setup
* **4 PM - 4.30 PM**: final documentation updates
* **4.30 PM - 5 PM**: app demos

## Tips
* Start with a basic network architecture, you can add image augmentation and transfer learning as time allows.
* Save your best model to a file and load it into your Streamlit app.
* You might want to have someone focus on building the Streamlit app relatively early in the process.
* In your presentation, tell us your model's improvement over baseline.
* TensorFlow's [ImageDataGenerator class](https://www.tensorflow.org/api_docs/python/tf/keras/preprocessing/image/ImageDataGenerator) can help you load your data.
* Make sure you use a GPU for any CNNs! Kaggle has GPUs available (and maybe TPUs - even faster, but might require code modification). You can choose the upgraded hardware under *Settings* -> *Accelerator*. You may need to register and confirm some information first. 🙂

![](https://i.redd.it/y583w8qasg121.jpg)

Created by: Greg (Chuck) Dye and adjusted by Jeff Hale
