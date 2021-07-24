# cls_06

1.数据爬取
使用imagedownloadmaster对图片进行爬取，需要future PySocks requests selenium PyQt5库
运行image_downloader_gui.py，出现gui界面，也可以通过命令行调用
usage: image_downloader.py [-h] [--engine {Google,Bing,Baidu}]
                           [--driver {chrome_headless,chrome,phantomjs}]
                           [--max-number MAX_NUMBER]
                           [--num-threads NUM_THREADS] [--timeout TIMEOUT]
                           [--output OUTPUT] [--safe-mode] [--face-only]
                           [--proxy_http PROXY_HTTP]
                           [--proxy_socks5 PROXY_SOCKS5]
                           keywords
                           
2.图像过滤
pip install umap-learn
pip install opencv-python
pip install matplotlib
pytorch

数据加载

修改相应文件的root_dir和file_suffix参数

运行初级数据筛选：
python img_primary_filter.py
运行高级数据筛选：
python img_advanced_filter.py
