## Short and handpick Go packages list.

### Date and Time

* github.com/golang-module/carbon/v2

### Serialization

* github.com/tidwall/gjson - simple than encoding/json
    ```go
    gjson.GetBytes(resp.Body(), "PCP.0.version")
    ```
* gopkg.in/yaml.v3

### File Processing

* github.com/xuri/excelize/v2

### Web

* github.com/go-resty/resty/v2
* github.com/PuerkitoBio/goquery
  ```go
  doc, err := goquery.NewDocumentFromReader(bytes.NewReader(resp.Body()))
  ...
  doc.Find("b").FilterFunction(...).First().Text()
  ```

### Web Framework

* github.com/gin-gonic/gin

### ORM

* gorm.io/gorm

### Database

* github.com/glebarez/sqlite

### Shell

* github.com/urfave/cli/v2
* github.com/fatih/color

### Version Structure

* github.com/coreos/go-semver
