Image Spam Detection
===
Published : https://doi.org/10.1080/19393555.2020.1722867

Spam can be defined as unsolicited bulk e-mail. In an effort to evade text-based filters, spammers sometimes embed spam text in an image, which is referred to as image spam. In this research, we consider the problem of image spam detection, based on image analysis. We apply convolutional neural networks (CNN) to this problem, we compare the results obtained using CNNs to other machine learning techniques, and we compare our results to previous related work. We consider both real-world image spam and challenging image spam-like datasets. Our results improve on previous work by employing CNNs based on a novel feature set consisting of a combination of the raw image and Canny edges.

Installation
---
1. Use python3 3.6 (other versions might not work)
2. Use requirements file to install everything
3. Some might need root permission

Ubuntu
---
```
sudo apt-get update
sudo apt-get install python3-dev python3-pip build-essential libzmq3-dev
sudo apt-get install graphviz

pip3 install -r requirements.txt
pip3 install jupyter

```
