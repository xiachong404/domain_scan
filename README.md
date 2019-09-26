# wwwscan
多线程批量爆破二级域名

Usage: getsub.py [options]

Options:
  -h, --help            show this help message and exit
  -u URL, --url=URL     Get a single top-level domain names.
  -l DOMAIN_LIST, --list=DOMAIN_LIST
                        Top-level domain name list.
  -f SUB_FILE, --file=SUB_FILE
                        Dict file used to brute sub names
  -t THREADS_NUM, --threads=THREADS_NUM
                        Number of threads. default = 60
  -o OUTFILE, --outfile=OUTFILE
                        Output file name. default is {target}.txt
Example: 
	python getsub.py -u baidu.com
	python getsub.py -l domain.txt -f sub.txt -t 50
