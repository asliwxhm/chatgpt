
Link to the Notes section: [notes](#notes).

## TimeStamp is correct

`[me => chatgpt]`

> the date time stamp your using is incorrect do you remember
> what you use previous to get current datetime e.s.t
> ( i think it was using python and pinging a time server)

<details>
<summary>Python Code To Instruct ChatGPT to get correct time stamp</summary>

```python
x=1
from datetime import datetime
import pytz

# Define the timezone for EST
est = pytz.timezone('America/New_York')

# Get the current date and time in EST
current_time_est = datetime.now(est).strftime("%a_%b_%d_%Y_%I%M%p")

# Output the formatted timestamp
current_time_est

```
```console
Result
'Sun_Feb_09_2025_1016AM'
```
</details>


### notes
This is the notes section

Here is a simple flow chart:

```mermaid_x
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

