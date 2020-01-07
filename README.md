# This whole repo is against Google Colab policy and you shouldn't be using it.
> **Why are hardware resources such as T4 GPUs not available to me?**
The best available hardware is prioritized for users who use Colaboratory interactively rather than for long-running computations. Users who use Colaboratory for long-running computations may be temporarily restricted in the type of hardware made available to them, and/or the duration that the hardware can be used for. We encourage users with high computational needs to use Colaboratory’s UI with a local runtime.
Please note that using Colaboratory for cryptocurrency mining is disallowed entirely, and may result in being banned from using Colab altogether.

<sub>Source: https://research.google.com/colaboratory/faq.html</sub>

# Torrent To Google Drive Downloader
Simple notebook to stream torrent files to Google Drive using Google Colab.

<a href="https://colab.research.google.com/github/FKLC/Torrent-To-Google-Drive-Downloader/blob/master/Torrent_To_Google_Drive_Downloader.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

### Tutorial
Click the badge which says 'Open in Colab' and follow directions there.

### What is the purpose of it?
1. Because of Google Servers' speed, I downloaded 12GB of a file and the average speed was 60MBPS.
2. Because it is in the cloud, by that I mean I can access it anywhere on my phone, tablet, etc without copying files around

### Frequently Asked Questions
1. **How to get more disk space**:

    > Go to Runtime -> Change Runtime and give GPU as the Hardware Accelerator.  
You will get around 384GB to download any torrent you want.

2. **Downloading missing files without re-downloading whole torrent**: If somehow some files are missing try to re-download torrent. Fastresume will check files.

For more questions check [existing issues](https://github.com/FKLC/Torrent-To-Google-Drive-Downloader/issues) or [open a new one](https://github.com/FKLC/Torrent-To-Google-Drive-Downloader/issues/new)
