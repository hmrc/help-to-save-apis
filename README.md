
# Help To Save API's

Contains JSON schemas for the Help To Save service along with samples and a python script that allows easy exploration.

## Version Map

Github version on left, ICD version on the right

/1.0 ICD 1.6 ... 2.0+ until next version map number appears below

## Validate

The validate script is written in python, and needs the jsonschema library to work. You can install this with the command ```pip install jsonschema``` if you have a standard python environment. Note that the script expects python to be in ```/usr/local/bin```.  This is the first line of the script and it would have to be changed for a windows installation or an enviroment where an alternative location is used. 

To validate a piece of JSON, use the command

```python
 ./validate my-json.json
```

The jsonschema library does not implement all of the latest [http://json-schema.org/] draft, so the schema contains some elements that are not yet in use.

### License

This code is open source software licensed under the [Apache 2.0 License]("http://www.apache.org/licenses/LICENSE-2.0.html").
​    
