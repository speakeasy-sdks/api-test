<!-- Start SDK Example Usage [usage] -->
```python
import api_test

s = api_test.APITest()


res = s.pets.create_pets()

if res.status_code == 200:
    # handle response
    pass
```
<!-- End SDK Example Usage [usage] -->