GigaPan_Downloader
==================
This is a fork from GigaPan Downloader
https://code.google.com/p/gigapan-downloader/

New BSD License

---

his script should be used to only download gigapan tiles that you have copyright permissions to use. Doing otherwise is a violation of the Terms of Service of Gigapan, Inc. and is expressly prohibited.

This Python 2.X script downloads gigapan pictures at their highest resolution.

How to run?
python downloadGigaPan.py <imageid>
For example:

http://www.gigapan.com/gigapans/54825
The <imageid> is 54825

python downloadGigaPan.py 54825
This will download the image tiles into directory "54825"

User snapshots(tags) locations and descriptions can be found at :

http://www.gigapan.com/gigapans/<imageid>/snapshots.json
This software is made available for research and non-commercial use only.

Citation
Saliency-Assisted Navigation of Very Large Landscape Images
C.Y. Ip, and A. Varshney
IEEE Transactions on Visualization and Computer Graphics 
17(12), 2011, pp 1737 - 1746.
@article{ip2011saliency,
  title={Saliency-assisted navigation of very large landscape images},
  author={Ip, C.Y. and Varshney, A.},
  journal={IEEE Transactions on Visualization and Computer Graphics},
  volume={17},
  number={12},
  pages={1737--1746},
  year={2011},
}

