# xiaoermei
s = requests.Session()
s.mount("/templates/xiaoermei/static",  StaticFiles(directory="static"))
