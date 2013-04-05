python-exacttarget
==================

Python Wrapper for Exact Target SOAP API.

EXAMPLE
=======

```python

from exacttarget.api import ExactTargetAPI

api_object = ExactTargetAPI('user', 'password')

# Generate oauth_token and initialize connection
api_object.init_client()

# Add data in Data_Extension
api_object.add_to_data_extension(
    'data_extension_id', [{'customer_email_address': 'customer@customer.com', 'product': '678'}]
)
```
