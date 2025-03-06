#  Bootable Kali & Tails USB with Presistance & Shared Encrypted Storage

## 📖 Table of Contents
- [Project Overview](#project-overview)
- [Partition Layout](#partition-layout)
- [Setup Instructions](#setup-instructions)
- [Screenshots](#screenshots)
- [Contact Me](#contact-me)



## **Project Overview**
This project demonstrates how to create a dual-boot USB stick running Kali Linux and Tails OS, each with its own encrypted persistent storage. It also includes shared encrypted and open storage.


## **Partition Layout**
| Partition           | Size   | File System | Encryption | Purpose                      |
|---------------------|--------|-------------|------------|------------------------------|
| **Kali Boot**      | 60GB   | FAT32        |  No       | Bootable Kali OS             |
| **Kali Persistence** | 60GB  | EXT4        |  LUKS     | Encrypted storage for Kali   |
| **Tails Boot**     | 16GB   | FAT32        |  No       | Bootable Tails OS            |
| **Tails Persistence** | 30GB | EXT4        |  LUKS     | Encrypted storage for Tails  |
| **Encrypted Storage** | 10GB | exFAT (VeraCrypt) |  Yes  | Secure private storage      |
| **Open Storage**   | 62GB   | exFAT       |  No       | General file storage         |

---

## **Technical Skills Demonstrated**
- **Disk Partitioning & File Systems** (FAT32, EXT4, exFAT)
- **Encryption & Security** (LUKS, VeraCrypt)
- **Linux System Administration** (Kali, Tails)
- **Bootable USB Creation** (Rufus, Balena Etcher)
- **Networking Basics** (Tails' Tor integration, secure connections)
- **Cybersecurity & Privacy** (Anonymous OS setup, persistent encrypted storage)

---

## **Setup Instructions**
1. Format the USB drive with GPT partitioning.
- asdasd
- asdasdasd
    - test 
    - sadsad
2. Create partitions using `diskpart` or Linux tools.
3. Flash **Kali Linux** and **Tails OS** using Rufus or Balena Etcher.
4. Enable **persistent encrypted storage** using LUKS.
5. Configure shared encrypted storage using **VeraCrypt**.

---

## **Screenshots**
Screenshots documenting each step are stored in the [`Screenshots`](./Screenshots) folder:
- `partition-layout.png` – Final USB partition setup
- `kali-installation.png` – Flashing Kali using Rufus
- `tails-persistence.png` – Setting up encrypted persistence in Tails

---

## **Contact Me**
- 📧 **Email:** [l.kedzielawski@gmail.com](mailto:l.kedzielawski@gmail.com)
- 💼 **LinkedIn:** [linkedin.com/in/lukasz-kedzielawski](https://www.linkedin.com/in/lukasz-kedzielawski/)
