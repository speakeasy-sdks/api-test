<!-- Start SDK Example Usage [usage] -->
```python
import api_test
from api_test.models import shared

s = api_test.APITest()

req = shared.Pet(
    id=596804,
    name='<value>',
)

res = s.pets.create_pets(req)

if res is not None:
    # handle response
    pass

```
<!-- End SDK Example Usage [usage] -->