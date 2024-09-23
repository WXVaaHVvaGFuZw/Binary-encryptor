# Binary-encryptor

此加密器是一个简单的文本加密和解密工具。

## 原理

1. **输入文本**：将输入文本先采用 Unicode 编码成十六进制代码。
2. **转换为二进制**：再将十六进制代码转为二进制代码。
3. **定义加密**：
   - 将二进制代码中的 `0` 用英文单引号 `'` 定义。
   - 将二进制代码中的 `1` 用英文双引号 `"` 定义。

## 效果

由于在 QQ 和微信聊天的默认字体中，英文单双引号的长相极其相似，难以区分，故极大地提高了加密效果。[doge]

 将这 `Hello World! 你好，世界！` 句话加密后将得到以下文本：
 
 `'''''''''"''"''''''''''''""''"'"'''''''''""'""'''''''''''""'""'''''''''''""'""""''''''''''"''''''''''''''"'"'"""'''''''''""'""""'''''''''"""''"''''''''''""'""'''''''''''""''"''''''''''''"''''"''''''''''"''''''"''""""'""''''''"'""''"'"""""'"""""""""''''""'''"''"""''''"'""''"""'"'"'"''""''""""""""'''''''"` 
 
 ![example](https://github.com/user-attachments/assets/f0e48d2d-f09d-42a3-8db6-9271399daf4a)
