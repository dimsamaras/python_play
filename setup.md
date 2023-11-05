HOWTO: Run codegen with python

1. Install venv: `pip install virtualenv`

1. Create and use dir

1. Create venv: `python<version> -m venv <virtual-environment-name>` 

    example: 
    ```
    mkdir projectA
    cd projectA
    python3.8 -m venv enveg 
    ```
1. Activate: `source env/Scripts/activate ` or linux `source env/bin/activate` 

1. Check packages: `pip list`

1. Install playwright: `pip install playwright`

1. Install playwright Chromium browser: `playwright install chromium` or Install all browsers: `playwright install`

1. Run codegen: `playwright codegen demo.playwright.dev/todomvc`

- Try the generaged tags in the borwser xpath css selector!

docs: https://playwright.dev/python/docs/codegen


Playwright for:
- Codegen
- Screenshot
- Videos