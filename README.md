# pytest-tips-tricks
---

## Step 1. Github codespace 
    - command
    ```
    which virtual
    virtualenv ~/.venv
    source ~/.venv/bin/activate
    ```
    - (optional) bash file managing
    ```
    vi ~/.bashrc
    (lowest line) source ~/.venv/bin/activate
    ```

    - Makefile writing
    ```
    touch Makefile
    ```

    - requirements.txt writing
    ```
    touch requirements.txt
    ```

## Step 2. Make
    - install
    ```
    make install
    ```

    - test
    ```
    make test
    ```

    - lint(code signing)
    ```
    make lint
    ```

    - All-in one
    ```
    make all
    ```
    
## Step 3. requirements version
    ```
    pip freeze | less
    ```


