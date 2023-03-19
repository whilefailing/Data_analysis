# Data_analysis
仿照谷歌分析写的埋点SDK以及可视化前端
## 埋点代码
    <script type="text/javascript">
        var _maq = _maq || [];
        _maq.push(['_setAccount', '网站标识']);
         
        (function() {
            var ma = document.createElement('script');
            ma.type = 'text/javascript';
            ma.async = true;
            ma.src = 'https:127.0.0.1:8888/ma.js';
            var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(ma, s);
        })();
    </script>
    如果想要对网站进行监视，请把此埋点代码放在网站js代码最上面（<head>下即可）
## 前端加载
npm run
## 后端加载
npm run dev
