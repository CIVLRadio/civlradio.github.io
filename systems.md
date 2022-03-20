# System Information

This page lists the different computers - both desktops and servers - involved in day-to-day operations at CIVL.

**For other equipment (network, audio, etc.), please see the [infrastructure](/infra.md) page.**

## Servers

### blackjack
- **Model:** Dell PowerEdge R720xd
- **OS:** Debian bookworm/sid
- **CPU:** 2x Intel Xeon E5-2695v2 @ 3.2 GHz
- **RAM:** 64 GB
- **Drives:**
  - 4x Western Digital WD Red Plus 10 TB (WD101EFBX)
  - 2x Samsung EVO 870 500 GB (MZ-77E500B/AM)
- **Details:** Purchased in November 2021 as a new central server for all major operations. Handles our main networked file share, the database for SAM Broadcaster, and the [now playing script](https://github.com/CIVLRadio/nowplaying).

### anemone
- **Model:** SuperMicro X10SLM-F
- **OS:** Debian stretch
- **CPU:** Intel Xeon E3-1231 v3 @ 3.8 GHz
- **RAM:** 8 GB
- **Drives:**
  - 2x Seagate NAS HDD 6 TB (ST6000VN0021)
  - 2x Seagate NAS HDD 2 TB (ST2000VN000)
  - 2x Samsung EVO 850 120 GB (MZ-75E120B/AM)
- **Details:** Formerly the central server, in the process of being phased out. Still handles live streaming and podcasting.

## Desktops

### Playout machine
- **Model:** HP Compaq 8100 Elite
- **OS:** Windows 7 Home Premium
- **CPU:** Intel Core i5-650 @ 3.2 GHz
- **RAM:** 4 GB
- **Drives:**
  - Seagate Barracuda ES.2 250 GB (ST3250310NS)
- **Details:** Circa 2010 hand-me-down from UFV ITS. Will eventually be replaced.

### Office workstations
- **Model:**
  - 6x HP Compaq 8000 Elite
  - 1x HP Compaq 8200 Elite
- **OS:**
  - 5x Windows 7 Professional
  - 2x Kubuntu 20.04 LTS
- **CPU:**
  - 6x Intel Core 2 Duo E8400 @ 3.0 GHz
  - 1x Intel Core i5-2400 @ 3.1 GHz
- **RAM:** 
  - 7x 4 GB
- **Drives:**
  - 1x Western Digital Scorpio Black 250 GB (WD2500BEKT0-66F3T2)
  - 1x Seagate Barracuda 250 GB (ST3250312AS)
  - 1x Western Digital Scorpio Black 250 GB (WD2500BEKT0-0PVMT0)
  - 3x Hitachi Travelstar 7K500 250 GB (HTS725025A9A364)
  - 1x N/A
- **Details:** Circa 2010 hand-me-downs from UFV ITS. Several have failing disk drives. Two are being used as testbeds for a move away from Windows. All are due to be retired and replaced.

### Audio workstations
- **Model:**
  - 2x Gigabyte B85M-D3H
  - 1x Gigabyte B250-HD3
- **OS:**
  - 2x Windows 7 Professional
  - 1x Windows 10 Professional
- **CPU:**
  - 2x Intel Core i5-4690 @ 3.5 GHz
  - 1x Intel Core i5-6600 @ 3.3 GHz
- **RAM:** 
  - 3x 8 GB
- **Drives:**
  - 3x Samsung EVO 850 250 GB (MZ-75E250B/AM)
- **Details:** Circa 2017 custom builds. Planning to add improved audio interfaces.

### Retired systems

- **barnacle:** Asus P7Q57-M, Win Server 2003 R2, former share server? Retired due to drive failure and virtualised onto anemone ca. 2016?
- **urchin:** n/a, FreeBSD, former streaming system, retired due to drive failure and functions relocated onto anemone
- **Old desktop #1:** Dell OptiPlex GX270, Windows XP?, retired due to drive failure
- **Old desktop #2:** MDG.ca/Seanix D865GLC, Windows XP Professional, retired due to end of useful life
