#Setup instructions

1. Have python 2.7.12 installed (2.7.13 is ok, nothing above 2.7.x)
2. ensure `pip` is installed and run `pip install -r requirements.txt`

## Running Tests:
from the root, run the following command:

### For Smoke Test: 
`robot -P . --include Smoke RFTests/TwoWilshire/`

### For Full Test: 
`robot -P . RFTests/TwoWilshire/`
 
