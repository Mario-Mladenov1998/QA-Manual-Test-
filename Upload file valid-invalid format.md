✅ Test Case 1 – Upload valid file
| Step | Action                | Test Data     | Expected Result             |
|------|------------------------|---------------|------------------------------|
| 1    | Open upload page       | –             | Upload page is loaded       |
| 2    | Choose a valid file    | file.pdf (1MB)| File is selected            |
| 3    | Click upload button    | –             | File is uploaded successfully |
| 4    | Check success message  | –             | Message shown: Upload successful |

Field	Value
Title	Upload valid file
Priority	Medium
Severity	Medium
Type	Positive
Precondition	User is on upload page



❌ Test Case 2 – Upload unsupported file format
pgsql
Копиране
Редактиране
| Step | Action                | Test Data     | Expected Result                    |
|------|------------------------|---------------|-------------------------------------|
| 1    | Open upload page       | –             | Upload page is loaded              |
| 2    | Choose unsupported file| file.exe (2MB)| File is selected                   |
| 3    | Click upload button    | –             | Error shown: File format not allowed |



Field	Value
Title	Upload unsupported file format
Priority	High
Severity	Medium
Type	Negative
Precondition	User is on upload page
