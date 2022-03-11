### PredictNextWords

- `getStories.py` to scrape data from http://www.classicshorts.com/ and store in `storyData.txt`
- `model_60.py` to train and store weights as `model_weights_saved_60.hdf5`
- `kerasServer_60.py` acts as server. Method is POST, url is localhost:5000, json body should have "inputText", optional "numWords" and "grammar_check"

