# spPY

Quick Start:

Using as a standalone script:
  - Set the groupname
  ```python
  groupname = "Production"
  ```

  - Add the users you want to be created
  ```python
  users = [
    "test@example.com",
    "test2@example.com"
  ]
  ```

 - Add component names you want to be created
  ```python
  components = [
    "Service 1",
    "Service 2"
  ]
  ```

  - Export your statuspage.io page id as STATUSPAGE_PAGE_ID
  ```bash
  export STATUSPAGE_PAGE_ID=XXXXXXXXXXXXX
  ```

  - Export your statuspage.io api key as STATUSPAGE_API_KEY
  ```bash
  export STATUSPAGE_API_KEY=XXXXXX-XXX-XXX-XXXXXXXX
  ```

  - Run the script
  ```bash
  ./statuspage.py
  ```