# Cross-Platform NAS & Network File Sharing

## Project Overview

Built a personal network-attached storage (NAS)-style file-sharing setup
that lets my Windows gaming PC and MacBook Air access the same files
over my home network. I configured an external 2 TB Seagate drive
connected to the MacBook Air and enabled macOS File Sharing using SMB
(Server Message Block).

## Goals

-   Create a shared storage location accessible from Windows and macOS.
-   Configure SMB file sharing and authenticate from a second computer.
-   Verify that files created on one device are accessible from the
    other.

## Hardware & Environment

-   **Host:** MacBook Air M3
-   **Storage:** 2 TB Seagate external drive
-   **Client:** Windows gaming PC
-   **Filesystem:** exFAT (GUID partition scheme)
-   **Sharing protocol:** SMB
-   **Network:** Local home network

## Implementation

1.  Connected and prepared the external drive, formatting it as exFAT
    with a GUID partition scheme.
2.  Enabled File Sharing in macOS settings and enabled SMB sharing.
3.  Configured the shared folder and used the Mac's local account
    credentials when connecting from Windows.
4.  Accessed the shared folder from the Windows PC.
5.  Verified that both computers could see the same shared files by
    creating a screenshot on Windows and opening it from the MacBook
    Air.

## Validation

-   Windows successfully connected to the Mac-hosted shared folder.
-   The same folder was visible from both devices.
-   A file created on the Windows PC was accessible from the MacBook
    Air.

## Skills Demonstrated

-   SMB network file sharing
-   Windows and macOS interoperability
-   Local network troubleshooting
-   User credential authentication
-   External storage and filesystem setup
-   Testing and validating shared-resource access

## What I Learned

This project gave me hands-on practice configuring a shared network
resource, authenticating from a different operating system, and testing
access across devices. These are useful foundational skills for IT
support, desktop support, and systems administration.

## Possible Next Steps

-   Configure a dedicated always-on host for shared storage.
-   Add a separate backup workflow for important files.
-   Review share permissions and test access with different user
    accounts.
-   Document connection and troubleshooting steps for future
    maintenance.

## Notes

The host's local IP address may change depending on the home network.
Use the current address of the MacBook Air when connecting from Windows.
Do not publish local account credentials or other private network
details in this repository.
