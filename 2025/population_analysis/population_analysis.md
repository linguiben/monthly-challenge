
World Population Prospects 2024: 
https://population.un.org/wpp/downloads?folder=Standard%20Projections&group=Mortality

中国统计年鉴.  
https://www.stats.gov.cn/search/s?tab=all&siteCode=bm36000002&qt=%E7%BB%9F%E8%AE%A1%E5%B9%B4%E9%89%B4

中国统计年鉴2024.  
https://www.stats.gov.cn/sj/ndsj/2024/indexch.htm

2024年人口数据.  
https://data.stats.gov.cn/easyquery.htm?cn=C01&zb=A0301&sj=2024


### 使用.venv虚拟环境
***在VSCode 中创建 Python venv环境***
http://vscode.github.net.cn/docs/python/environments  

```python
1. (cmd + shift + p), 搜索 Python: Create Environment，选择python版本，vscode将开始自动创建venv
   python3 -m venv .venv # 手动创建venv
2. 激活venv, (cmd + shift + p)，搜索 python: Select Interpreter
   ** 注意需要在vscode中打开文件夹，否则无法激活venv **
   ** 若无法自动激活(例如使用了power shell)，则手动激活： 
   .\.venv\Srcipts\active.bat # windows
   source .venv/bin/activate # linux
3. 激活venv后，使用pip安装依赖包: 
   pip install <package_name> 
     or pip install -r requirement.txt(若有此文件)
4. 查看已安装列表: 
    pip list
5. deactivate #退出venv
6. 生成依赖列表
   pip freeze > requirement.txt
```


