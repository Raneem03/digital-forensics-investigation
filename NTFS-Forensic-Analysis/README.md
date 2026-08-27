# NTFS Forensic Image Examination

Practical digital forensics lab focused on examining an NTFS forensic image using FTK Imager Lite.

## Objective

The objective was to examine an NTFS forensic image, identify file-system structures, inspect metadata, and examine file signatures.

## Tool

- FTK Imager Lite

## Evidence

- NTFS forensic image
- C2Proj3.E01

## Activities

- Loaded the forensic image into FTK Imager Lite.
- Identified the NTFS file system.
- Examined the root directory.
- Investigated NTFS system structures including:
  - $MFT
  - $MFTMirr
  - $BadClus
  - $Secure
  - [orphan]
- Examined file properties and metadata.
- Checked file signatures using hexadecimal data.
- Examined deleted-file information.
- Removed the evidence item after examination.

## Forensic Concepts

- NTFS file-system structures
- Master File Table (MFT)
- File metadata
- File signatures
- Deleted-file analysis
- Forensic image examination

## Skills Demonstrated

- Forensic image handling
- NTFS analysis
- FTK Imager usage
- File-system artifact examination
- Metadata and file-signature analysis
