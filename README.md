<!--
 * @Author: ShAn_3003
 * @Date: 2024-04-23 15:20:49
 * @LastEditTime: 2024-04-23 15:32:35
 * @LastEditors: ShAn_3003
 * @Description: 
 * @FilePath: \Github\README.md
-->
# shan.github.io 
## The First Commit-About some error I encountering When I install the opencv
Recently I wanna use opencv to finish some work about computer vision, So i try to install opencv in my computer.  

Firstly, I create a new visual environment by conda.
```bash
conda create --name opencv
```
To ensure there don't have any interrupt between all packages.  

Secondly, I install the opencv package by conda .  
```bash
conda install opencv
```

Hitherto i have finish download opencv and i try to import cv2.

```bash
python -m "import cv2"
```

It occurs the error message "No Module Named cv2" . 

But when I list my package , there do exist opencv .

I don't know why ???

### Solution

Only use Pip can finish this error.

```bash
pip install opencv-python
```