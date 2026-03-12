HAKURIN 官网部署说明

文件说明：
- index.html     网站主文件
- style.css      样式文件
- script.js      三语切换与房源卡片逻辑
- vercel.json    Vercel 部署配置

上传到 Vercel 的方法：
1. 打开 https://vercel.com/
2. 登录后点击 Add New... → Project
3. 如果你没有 GitHub 仓库，也可以先把这几个文件放进一个新文件夹，上传到 GitHub
4. 在 Vercel 里导入这个仓库
5. 部署完成后，在 Settings → Domains 里添加：
   - hakurinkyoto.com
   - www.hakurinkyoto.com
6. 按 Vercel 提示去你的域名商后台修改 DNS

推荐 DNS：
- A 记录：@  -> 76.76.21.21
- CNAME：www -> cname.vercel-dns.com

说明：
- 这是静态网站，不需要 Node 服务器
- 双击 index.html 也可以本地预览
