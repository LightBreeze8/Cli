# Soundness CLI

```
brew update && brew upgrade
curl -sSL https://raw.githubusercontent.com/soundnesslabs/soundness-layer/main/soundnessup/install | bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```


**更新bash配置文件（macOS默认可能用zsh而非bash，两个都试一下，报错了就使用另一个）**

```
source ~/.bashrc
source ~/.zshrc
```

**输入完后重新打开终端再输入以下内容：**

```
soundnessup install
soundnessup update  
soundness-cli generate-key --name my-key
```

**查看助记词(助记词一定要保存好)：**
```soundness-cli export-key --name my-key```  

要多号的话把my-key后面加个数字即可，如：
```
soundness-cli generate-key --name my-key1
soundness-cli export-key --name my-key1

soundness-cli generate-key --name my-key2
soundness-cli export-key --name my-key2

soundness-cli generate-key --name my-key3
soundness-cli export-key --name my-key3
```
