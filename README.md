# RL Utility Meter Distributions

## Description

Zip distributions of files needed for pi meter reader

## Meter Pi Distributions

| Date       | Filename              | Download Link                                                                                               |
| ---------- | --------------------- | ----------------------------------------------------------------------------------------------------------- |
| 2021-12-09 | meter_pi_dist_v01.zip | https://github.com/Radiator-Labs/meter_reader_pi_dist/raw/main/meter_pi_distributions/meter_pi_dist_v01.zip |

### Download Instructions

On the Raspberry Pi you can use the `wget` command to download the zip of your choice. Just replace the url with the matching version from the table above

```bash
wget https://github.com/Radiator-Labs/meter_reader_pi_dist/raw/main/meter_pi_distributions/meter_pi_dist_v01.zip
```

## OpenCV Installation Script

Scripts to install OpenCV on a Raspberry Pi 4 with 32bit OS

| OpenCV Version | Download Link                                                                                  |
| -------------- | ---------------------------------------------------------------------------------------------- |
| 4.5.4          | https://github.com/Radiator-Labs/meter_reader_pi_dist/blob/main/opencv_scripts/OpenCV-4-5-4.sh |

### Download Instructions

On the Raspberry Pi you can use the `wget` command to download the script of your choice. Just replace the url with the matching version from the table above.

```bash
wget https://github.com/Radiator-Labs/meter_reader_pi_dist/blob/main/opencv_scripts/OpenCV-4-5-4.sh
```

Before running the script you must first use chmod to make the script executable with the following command

```bash
sudo chmod 755 ./OpenCV-4-5-4.sh
./OpenCV-4-5-4.sh
```

> Remember to replace `OpenCV-4-5-4.sh` with the filename of the script you downloaded

## Notes

This repo uses git large file storage as the zip files are quite large (~100MB), when working locally with the repository make sure you have Git LFS enabled. [Git LFS Installation Instructions](https://git-lfs.github.com/)
