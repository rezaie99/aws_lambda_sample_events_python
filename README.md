[![Coverage Status](https://coveralls.io/repos/github/irlrobot/python_lambda_sample_events/badge.svg?branch=master)](https://coveralls.io/github/irlrobot/python_lambda_sample_events?branch=master)
[ ![Codeship Status for irlrobot/python_lambda_sample_events](https://codeship.com/projects/938444a0-d5be-0133-1313-7edf9ccff8c4/status?branch=master)](https://codeship.com/projects/142651)
# Python module for creating sample events to test AWS Lambda functions.

# Supported Services
* Codepipeline

# Usage Example
```python
from lambda_sample_events import SampleEvent
from pprint import pprint
codepipeline = SampleEvent('codepipeline')
pprint(codepipeline.event)
```
