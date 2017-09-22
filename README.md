# Cloud-Machine-Learning-APIs-Demo
1. Natural Language
    a. entity.py helps us extract all entities from our input text.
    b. request.json is the input body to be given to any HTTP client for testing web services (eg Postman).
2. Speech
    a. speech.py helps us take a flac encoded recording and translate it to text. You could demo with hint and without it.
    b. request.json is the input body to be given to any HTTP client for testing web services (eg Postman). Demo should be         done with and without phrases parameter.
    c. recording.flac is the flac encoded version of recording.m4a and it should be present in our Cloud Storage Bucket.
3. Translate
    a. translate.py helps us translate the any text to the required client language.
    b. nmt.py uses the neural model translation model explicitly.
4. Vision
    a. landmark.py helps us detect landmark locations, score, longitude and latitude.
    b. request.json is the input body to be given to any HTTP client for testing web services (eg Postman) and helps us detect      labels for any image stored in the Google Cloud Storage
