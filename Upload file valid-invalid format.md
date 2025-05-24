✅ Test Case 1 – Upload valid file
| Field         | Value                                |
|---------------|--------------------------------------|
| Test Case ID  | TC-UPLOAD-001                        |
| Title         | Upload valid file                    |
| Type          | Positive                             |
| Priority      | Medium                               |
| Severity      | Medium                               |
| Precondition  | User is on the upload page           |

| Step | Action                | Test Data       | Expected Result                   |
|------|------------------------|------------------|------------------------------------|
| 1    | Open upload page       | –                | Upload page is loaded             |
| 2    | Choose valid file      | file.pdf (1MB)   | File is selected                  |
| 3    | Click upload button    | –                | File is uploaded successfully     |
| 4    | Check success message  | –                | Message shown: Upload successful  |



❌ Test Case 2 – Upload unsupported file format
| Field         | Value                                      |
|---------------|--------------------------------------------|
| Test Case ID  | TC-UPLOAD-002                              |
| Title         | Upload unsupported file format             |
| Type          | Negative                                   |
| Priority      | High                                       |
| Severity      | Medium                                     |
| Precondition  | User is on the upload page                 |

| Step | Action                  | Test Data        | Expected Result                        |
|------|--------------------------|------------------|-----------------------------------------|
| 1    | Open upload page         | –                | Upload page is loaded                  |
| 2    | Choose unsupported file  | file.exe (2MB)   | File is selected                       |
| 3    | Click upload button      | –                | Error shown: File format not allow
