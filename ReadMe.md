﻿# Try Kernel

## 概要

Try Kernelはマイコン用の超軽量リアルタイムOSです。リアルタイムOSの極々基本的な機能のみを提供します。
Try Kernelは、CQ出版(株) Interface 2023年7月号の特集「ゼロから作るOS」に向けて作成し、このリポジトリでメンテしています。
なお、前述の記事の配布プログラムは以下から入手できます。

<https://github.com/ytoyoyama/interface_trykernel>

## 対象H/W・開発環境など

- RaspberryPy Pico
- Eclipse IDE for Embedded C/C++ Developers
- GNU Arm Embedded GCC

## ライセンスについて

本プログラムはMITライセンスの下でオープンソースとして公開します。著作権および許諾表示を記載すれば、非営利、商用を問わず、使用、改変、複製、再頒布が可能な制限の緩いライセンスですので、本プログラムをOSの自作に活用いただけたらと思います。ライセンスの詳細については、同梱のLICENSEをご参照ください。  
ただし、ブートコードの一部でPico C/C++ SDKのオブジェクトコードを利用してますので、それについてはPico C/C++ SDKのライセンスが適用されます。ソースファイルの冒頭に記載したライセンスに従ってください。このライセンスも厳しい制約はありません。該当するファイルは以下です。  

boot\boot2.c  
