# Text-to-speech-bot
<br>
curl -X POST -u "apikey:gCxbeqlK6LmNbMFvMDDD3x3lIbOWlS53Be__nB4C-t5t" \
--header "Content-Type: application/json" \
--header "Accept: audio/wav" \
--data "{\"text\":\"hey my name is Rahul Mishra and I belong from Ayodhya Uttar pradesh and I persuing my graduation in BBD university at lucknow in Data science and Artificial intelligence.\"}" \
--output Rahul.wav \
"https://api.au-syd.text-to-speech.watson.cloud.ibm.com/instances/74bce09b-62f0-4315-a6b9-dc760d78ec89/v1/synthesize?voice=en-US_MichaelV3Voice"
