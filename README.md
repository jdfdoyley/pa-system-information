# Task 2 – System Information

You are going to create a second program named PA1_SystemInfo.py.  Go to File and select new File.  Save the new screen as PA1_SystemInfo and click the save button.

Add the following lines

```Python
import wmi

c = wmi.WMI()
my_system = c.Win32_ComputerSystem()[0]

print(f"Manufacturer: {my_system.Manufacturer}")
print(f"Model: {my_system. Model}")
print(f"Name: {my_system.Name}")
print(f"NumberOfProcessors: {my_system.NumberOfProcessors}")
print(f"SystemType: {my_system.SystemType}")
print(f"SystemFamily: {my_system.SystemFamily}")
```

Now run the program.  Take a screenshot of your output

## Deliverables for Task 2

- Screenshot for your completed wmi program with 5 items.
