# GitHub-VScode 教學

* 這份文件說明如何使用 Visula Studio Code (VSCode) 來進行 GitHub 上程式碼資料的下載與上傳
* 首先電腦端必須安裝 Git 這個軟體，請參考以下網址下載，並一路按到底。
https://git-scm.com/


## A-1. 從 GitHub 上下載：利用終端機指令

### Step 1. 首先先找到一個想下載的程式碼，可以是別人公開分享的，也可以是自己 Repository 所儲存的程式碼。

### Step 2. 按照下圖所規定的順序複製這份扣的網址。

![1](https://user-images.githubusercontent.com/91120147/161050561-012fa3bd-9cb8-4617-8e8d-9e2e9ff5ab7d.png)

### Step 3. 開啟一個空資料夾，並且以滑鼠右鍵點資料夾空白處，選擇 `以Code開啟`

![2](https://user-images.githubusercontent.com/91120147/161050568-87263ad8-e691-4f6d-9483-397fedc2cf3e.png)

### Step 4. 打開 VSCode 之後， `ctrl + ~` 打開終端機，並且輸入
```
git clone <你剛剛複製的網址>
```
### 以圖中為例，輸入了以下指令
```
git clone https://github.com/yangrui9501/Arduino_Example_LED.git
```

![3](https://user-images.githubusercontent.com/91120147/161050570-2fbe137c-cb98-42ea-94ae-6377de941fcb.png)

### Step 5. 最後結果如下：

![4](https://user-images.githubusercontent.com/91120147/161050571-d6fe9f74-a6d0-462d-85aa-a60b83128954.png)


## A-2. 從 GitHub 上下載：利用指令集
利用 VS Code 下載資料還有其他方式。首先必須前二個步驟跟 A-1 章節相同，必須先複製程式碼所在的網址。

### Step 3. 開啟 VS Code，並且按下F1開啟指令集，輸入 `git clone` 並按下 Enter。

![c1](https://user-images.githubusercontent.com/91120147/161374561-49e76100-540b-4ad9-b110-38876b33989b.png)

### Step 4. 在接下來跳出來的視窗，輸入剛剛複製的網址，並按下 Enter。

![c2](https://user-images.githubusercontent.com/91120147/161374567-2ff766f4-1e3b-4c89-9113-8a564d74c1bc.png)

### Step 5. 接下來會要你選擇儲存庫位置，可以選擇已經存在的資料夾，也可以自己新建一個資料夾，以下為新創立一個資料夾。

![c3](https://user-images.githubusercontent.com/91120147/161374570-618d6688-d97d-4a31-a5a4-55f7426bb82f.png)

### Step 6. 如圖，可以按開啟或者在新視窗開啟。差別在於前者會直接將剛剛克隆的資料在這個 VS Code 視窗開啟，後者則會新開一個 VS Code 視窗並開啟。

![c4](https://user-images.githubusercontent.com/91120147/161374571-ac4068f5-ac28-4c72-91ed-c94d0740aa5a.png)

### Step 6. 最後，按下信任作者，就可以對這份程式碼做壞壞的事情。
![c5](https://user-images.githubusercontent.com/91120147/161374572-16e3349a-2eca-423a-a043-364d4d690cb4.png)

## A-3. 直接下載zip檔，解壓縮後用 VS Code 開啟。
嗯，這件事情太簡單了。

## B-1. 程式碼上傳：對於尚未在 GitHub 上 Repositories 建立資料夾者 (第一次上傳)

### Step 1. 首先，打開一個資料夾，把想上傳的東西丟進去，並且空白處右鍵點選 `以code開啟`。

![b1](https://user-images.githubusercontent.com/91120147/161057636-14c94242-9ef4-4a9d-9236-e46e456cb862.png)

### Step 2. 按照圖中紅框進行點選。

![b2](https://user-images.githubusercontent.com/91120147/161057618-4d7383d4-4c37-4ae2-9e59-15f9b34ba1fc.png)

### Step 3. 按是啦哪次不按是。

![b3](https://user-images.githubusercontent.com/91120147/161057628-87d6bf52-df5c-4745-81cd-cedc67ce5b71.png)


### Step 4. 會出現一個下滑框，這是要輸入這次版本更新的commit。並不是一定要輸入。

![b4](https://user-images.githubusercontent.com/91120147/161057629-d8665449-e505-4c94-951c-f36da8a668f0.png)

### Step 5. 按發布分支。

![b5](https://user-images.githubusercontent.com/91120147/161057630-c336a3e9-0f21-4016-a1d1-2520ebe4f757.png)

### Step 6. 接下來可以選擇要上傳的資料是否要公開。如果是 public 就是公開， private 就是不公開。

![b6](https://user-images.githubusercontent.com/91120147/161057632-2ca2d617-d5a1-43cb-af1f-aaf441cdfe98.png)

### Step 7. 最後在你自己的 Repositories 就可以看到剛剛上傳的資料了

![b7](https://user-images.githubusercontent.com/91120147/161057635-618236d4-910c-434a-9cf3-7fd25a3e5653.png)


## B-2 程式碼上傳：對於同一份程式碼第二次以後的上傳
對於同一份程式碼，如果在電腦端有了這些異動，該如何再次上傳 GitHub 進行雲端備份與版本控制呢？本章節將介紹此議題。

### Step 1. 隨便改一下你的 Code，然後按圖中 2. 的地方。

![d1](https://user-images.githubusercontent.com/91120147/161376757-db635a21-9a6c-4ddb-bd57-0f2e0cc30095.png)

### Step 2. 按下勾勾表示認可。再按是儲存認可。

![d2](https://user-images.githubusercontent.com/91120147/161376761-84c54836-5e60-479e-a270-6629768d9be9.png)

### Step 3. 接下來會跳出一個下滑視窗，可以打一些字來描述一下這次更新程式碼的快樂之情。

![d3](https://user-images.githubusercontent.com/91120147/161376762-4b857702-aaeb-48fa-a6f4-8492aff71ae5.png)

### Step 4. 按同步變更就可以上傳了。

![d4](https://user-images.githubusercontent.com/91120147/161376763-2789669a-4ac2-4c79-ac07-d18c538f3dce.png)

### Step 5. 回到剛剛的 GitHub 頁面，可以發現程式碼已經成功上傳了，並且剛剛的 commit 2 也出現在圖中的紅框處。那個其實可以點下去。

![d5](https://user-images.githubusercontent.com/91120147/161376926-fbd25f08-a1e2-4a5f-9d86-8fbea5e74c5e.png)


### Step 6. 按下去之後就會出現這些東西，會顯示說這些程式碼被更動了哪些部分，並且也可以之前的版本並不會直接被覆蓋掉，仍然可以把它們叫出來，方面我們進行版本控制。

![d6](https://user-images.githubusercontent.com/91120147/161376765-c64796da-b929-4428-88b4-d749b6a4a8c3.png)
