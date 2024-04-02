# Prepare ENV
Note: Scrapy-playwright not support window so all step using on Linux
1. Install python3, pip, venv
    - sudo apt update
    - sudo apt install python3 python3-pip
    - pip3 install virtualenv
2.  Start scrapy, scrapy-playwwright, chronium
    -  mkdir scrapy-playwright-project
    -  cd scrapy-playwright-project
    -  python3 -m venv env
    -  . env/bin/activate
    -  pip3 install scrapy 
    -  export PATH=$PATH:$HOME/.local/bin
    -  pip3 install scrapy-playwright
    -  python3 -m playwright install chromium
    -  python3 -m playwright install-deps chromium

# Site Search Poc



## Getting started
    - git clone  https://gitlab.tma.com.vn/crawl-poc/site_search_poc.git
    - cd site_search_poc
    - scrapy crawl poc-crawl