[![Build Status](https://travis-ci.org/engineerbeard/hangouts_parser.svg?branch=master)](https://travis-ci.org/engineerbeard/hangouts_parser)
[![Go Report Card](https://goreportcard.com/badge/github.com/engineerbeard/hangouts_parser)](https://goreportcard.com/report/github.com/engineerbeard/hangouts_parser)
# Google Hangout JSON parser.
Extract data from google hangout json file. At this point it only extracts
conversation data. If you dont wish to compile yourself, just grab the latest build from
the release tab.
### Format
* timestamp, conversation_id, participants, text
### Usage:
* ./<platform>_hangout_parser -jsonfile=your_json_file.json > outputfile.csv


