# nk-repository
this is my tasks
import time

# Local time (based on phone/system)
local_time = time.asctime(time.localtime())
print("Local Time:", local_time)

# UTC time
utc_time = time.asctime(time.gmtime())
print("UTC Time:", utc_time)