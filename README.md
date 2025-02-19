# LIG_Geoparsing
Notebooks of Geoparsing in LIG3 using LLM: Claude, deepseek, Chatgpt-4o, Llama, Mistral and so on

# Notebook explain
1_remove_person_names.ipynb
Data mapper downloaded from Hamburg parliament database website PDFs need to preprocess texts and remove personal names using ner-ger-large model from Huggingface.
https://huggingface.co/flair/ner-german-large

2_prompt_with_ollama.ipynb
Example how you can prompt with Ollama on GPU cluster, we recommand you to run this notebook on GPU machine.

3_mapbox_geocoding-forgit.ipynb
Using hamburg address database to geocode location that has been extracted by LLMs. Those can not find coordinate were further processed by Mapbox and Nominatim Geocoder.

4_geocode_nominatim_spatial_join.ipynb
Python script to compare location rows from different model location extraction results. Using project to UTM, buffer and spatial outer join approaches.
