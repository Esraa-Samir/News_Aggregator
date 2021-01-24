
# News Aggregator

To run the project you need to:
- Create venv
- Activate venv
- pip install -r requirements.txt
- cd .../app
- uvicorn main:app --reload

To run unit tests use the following command:
- pytest ../tests/test_main.py


APIs:
- /news : is expected to lis allt news from 2 resources (Reddit.com and NewsAPI)
- /news?query=<keyword> : is expected to list news related to provided keyword
