---


---

<h1 id="林煜霖eason-lin">林煜霖(Eason Lin)</h1>
<p>學經歷: 中央大學資管所<br>
Email: <a href="mailto:eason4522@gmail.com">eason4522@gmail.com</a></p>
<h1 id="作品集">作品集</h1>
<h2 id="使用-golang-在-docker-上實作廣告投放api">使用 Golang 在 Docker 上實作廣告投放(API)</h2>
<p><a href="https://github.com/foxdog1011/Backend_work">https://github.com/foxdog1011/Backend_work</a></p>
<h2 id="使用-minikube-實作-wordpress-mysql">使用 Minikube 實作 Wordpress+ mysql</h2>
<ol>
<li>創建一  Secret 物件，存放 Wordpress application 存取 Mysql server 的密碼<br>
<img src="https://github.com/foxdog1011/Eason-Lin/blob/master/01.04.2024_14.59.36_REC.png?raw=true" alt="enter image description here"></li>
<li>確認 Minikube 運行狀況<br>
<img src="https://github.com/foxdog1011/Eason-Lin/blob/master/01.04.2024_15.03.30_REC.png?raw=true" alt="enter image description here"></li>
<li>創建一個 Deployment 物件去管理 Wordpress 服務</li>
</ol>
<p><img src="https://github.com/foxdog1011/Eason-Lin/blob/master/01.04.2024_15.05.56_REC.png?raw=true" alt="enter image description here"><br>
4. 創建一個 Service 物件，讓本機端的瀏覽器也可以訪問到 Kubernetes Cluster 中的 wordpress-deployment 物件<br>
<img src="https://github.com/foxdog1011/Eason-Lin/blob/master/01.04.2024_15.09.26_REC.png?raw=true" alt="enter image description here"><br>
5. 透過 Minikube service 找到 wordpress-service 的 url<br>
6. 打開本機端瀏覽器輸入找到的網址，即可進到 Wordpress application 的設定頁面<br>
<img src="https://github.com/foxdog1011/Eason-Lin/blob/master/01.04.2024_15.12.10_REC.png?raw=true" alt="enter image description here"></p>
<h2 id="使用-minikube-實現排程服務">使用 Minikube 實現排程服務</h2>
<ol>
<li>透過設定檔創建一個名稱為 hello 的 cronjob，在每一分鐘的時候都能在 kubernetes 上運行 echo “hi current time is ${date}” 的指令<br>
<img src="https://github.com/foxdog1011/Eason-Lin/blob/master/01.04.2024_15.58.59_REC.png?raw=true" alt="enter image description here"></li>
<li>該 cronjob 已執行，可透過指令即時查看目前 job 的運行狀況<br>
<img src="https://github.com/foxdog1011/Eason-Lin/blob/master/01.04.2024_16.05.17_REC.png?raw=true" alt="enter image description here"></li>
</ol>
<h2 id="建立jenkins-pipeline-結合專案項目">建立Jenkins Pipeline 結合專案項目</h2>
<ol>
<li>透過 maven 構建項目</li>
<li>透過 sonarqube 做代碼檢測</li>
<li>docker build image</li>
<li>將 image 推送到 harbor<br>
<img src="https://github.com/foxdog1011/Eason-Lin/blob/master/01.04.2024_16.24.33_REC.png?raw=true" alt="enter image description here"></li>
</ol>
<h2 id="專業技能">專業技能</h2>
<ol>
<li>熟悉K8S，使用 K8S 來管理各個容器</li>
<li>熟悉JENKINS，進行 Pipeline 排程</li>
<li>熟悉  GIT，能多人完成共同專案</li>
<li>熟悉 Python 語法</li>
<li>能利用 Python 完成各項數據分析</li>
</ol>
<h2 id="相關證照">相關證照</h2>
<p><img src="https://github.com/foxdog1011/Eason-Lin/blob/master/%E5%A4%9A%E7%9B%8A%E8%AD%89%E6%9B%B8.jpg?raw=true" alt="enter image description here"></p>
<p><img src="https://github.com/foxdog1011/Eason-Lin/blob/master/%E4%B8%8B%E8%BC%89.png?raw=true" alt="enter image description here"><br>
<img src="https://github.com/foxdog1011/Eason-Lin/blob/master/%E4%B8%8B%E8%BC%89%20%281%29.png?raw=true" alt="enter image description here"><br>
<img src="https://github.com/foxdog1011/Eason-Lin/blob/master/%E4%B8%8B%E8%BC%89%20%282%29.png?raw=true" alt="enter image description here"></p>

