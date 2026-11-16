# First Autopsy Digital Forensics Practical

## 1. Project Overview
This project is a beginner digital forensics exercise using Autopsy. The purpose was to practise examining sample digital files, reviewing metadata and calculating file hashes.

## 2. Tool Used
- Autopsy

## 3. Evidence Description
Three fictional text files were created for this educational exercise:

- Project_Notes.txt
- Investigation_Log.txt
- Readme.txt

The files were added to Autopsy as a Logical Files data source.

## 4. Examination Process
The following activities were performed:

1. Created a forensic case in Autopsy.
2. Added the three sample files.
3. Examined file metadata.
4. Reviewed file names, sizes and MIME types.
5. Recorded MD5 and SHA-256 hash values.
6. Created a separate copy of Project_Notes.txt.
7. Modified the copy and added it as a separate data source.
8. Compared the SHA-256 values of the original and modified copy.

## 5. Findings
- The three original sample files were successfully added and examined.
- File names, sizes and MIME types were visible.
- Timestamp fields displayed zero values in the examination.
- MD5 and SHA-256 values were available and recorded.
- The original file and modified copy had different SHA-256 values.

## 6. Conclusion
This practical demonstrated how Autopsy can be used to examine logical files, review metadata and calculate file hashes.

The hash comparison showed how a change in file contents can be detected by comparing SHA-256 values.

## 7. Learning Outcomes
I gained introductory practical experience in:
- Creating a forensic case.
- Adding logical files as a data source.
- Examining file metadata.
- Understanding MD5 and SHA-256 hashes.
- Performing a basic file integrity comparison.

**Project Status:** Completed beginner practice exercise.
