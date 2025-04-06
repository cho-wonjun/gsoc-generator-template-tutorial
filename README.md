Result:
```

> python-mqtt-client-template@0.0.1 test
> npm run test:clean && npm run test:generate && npm run test:start


> python-mqtt-client-template@0.0.1 test:clean
> rimraf test/project/client.py


> python-mqtt-client-template@0.0.1 test:generate
> asyncapi generate fromTemplate test/fixtures/asyncapi.yml ./ --output test/project --force-write --param server=dev

┌  AsyncAPI Generator
│
◇  Check out your shiny new generated files at test/project.


> python-mqtt-client-template@0.0.1 test:start
> python test/project/test.py

New temperature detected 35375314 sent to temperature/changed
Temperature drop detected 35375314 sent to temperature/dropped
Temperature rise detected 35375314 sent to temperature/risen
```
