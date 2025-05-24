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
