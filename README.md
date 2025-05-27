这是我的大学毕业设计项目 没有使用现成的读取二维码的库 而是使用Python完全自己重现了一边如何读取二维码 其中包含了读取图片 根据边缘检测寻找二维码并切割二维码 将二维码的黑白模块变换成0与1储存进入矩阵 进行反掩码处理 根据里德所罗门纠错码对数据进行纠错并且解码编辑的数据
代码中UItest是主函数 

This is my undergraduate graduation project. I did not use any existing QR code reading libraries—instead, I implemented the entire QR code reading process from scratch using Python. This includes loading the image, detecting the edges to locate and extract the QR code, converting the black and white modules into 0s and 1s to store in a matrix, applying unmasking, and performing error correction and decoding of the encoded data using Reed-Solomon error correction codes.
The main function is in the UItest．py file.

