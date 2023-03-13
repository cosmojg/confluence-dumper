## How to Install

### Configure Confluence Dumper

Install dependencies:

    pip install -r requirements.txt

Copy settings template:

    cd confluence_dumper
    cp settings.sample.py settings.py

Update `settings.py` to reflect your specific Confluence instance

## How to Use

Run confluence dumper:

    cd confluence_dumper
    python confluence_dumper.py
