# Url-Shorten-Worker
A URL Shortener created using Cloudflare Worker

# API

[中文API文档](API.md)

# Getting start
### 去Workers KV中创建一个命名空间

Go to Workers KV and create a namespace.

<img src="https://cdn.jsdelivr.net/npm/imst@0.0.4/20201205232805.png">

### 去Worker的Settings选选项卡中绑定KV Namespace

Bind an instance of a KV Namespace to access its data in a Worker.

<img src="https://cdn.jsdelivr.net/npm/imst@0.0.4/20201205232536.png">

### 其中Variable name填写`LINKS`, KV namespace填写你刚刚创建的命名空间

Where Variable name should set as `LINKS` and KV namespace is the namespace you just created in the first step.

<img src="https://cdn.jsdelivr.net/npm/imst@0.0.4/20201205232704.png">

### 复制本项目中的`index.js`的代码到Cloudflare Worker 

Copy the `index.js` code from this project to Cloudflare Worker. 

### 点击Save and Deploy

Click Save and Deploy

# Demo
~~https://5it.me~~

## Demo由于被人滥用，使用短链接引导用户至恶意网站，目前已被域名服务商停止解析，如需使用请自行搭建。
## Demo has been abused by people using short links to lead users to malicious websites, and has been stopped by the domain name service provider, if you need to use it, please build your own
 
Note: Because someone abuse this demo website, all the generated link will automatically expired after 24 hours. For long-term use, please deploy your own.

注意：由于该示例服务被人滥用，用于转发诈骗网站，故所有由demo网站生成的链接24小时后会自动失效，如需长期使用请自行搭建。
