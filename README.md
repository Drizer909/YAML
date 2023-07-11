
## YAML (YAML Ain't Markup Language) prev - yet another markup language

YAML files are like spreadsheets, but for computers.
Just like a spreadsheet, a YAML file can store data in a table-like format. But unlike a spreadsheet, a YAML file is written in a human-readable format that is easy for computers to understand. This makes YAML files ideal for storing configuration data, such as the settings for a software application.

Eg:

```yaml
name: Shivam
age: 21
address: !!omap
  city: Delhi
  state: New- Delhi
  country: India
  phone: !!seq
    office: !!int 3462873
    home: 
        - 1111111
        - 2222222
```

## Learning Resources (highly recommanded for yaml learn)
- [Complete YAML Course](https://youtu.be/IA90BTozdow)


## Properties

- Easy to read & simpler then json and xml files 
- We can't add commands.
- Nice Strict syntax - (Indentation)


## Usage

- Used in Kubernetes, Docker
- Used to store data in key-value pairs.
- CI/CD tools like GitHub Actions, CircleCI, use YAML to create workflows.

#### Yaml devops tool that gonna help u surely 
- [YAML Validator](https://codebeautify.org/yaml-validator) - Check the the format of the file.
- [YAML to JSON](https://codebeautify.org/yaml-to-json-xml-csv) - Convert YAML to JSON.
- [YAML LENS](https://k8slens.dev/) - for objectfiles into codebase files automatically
- [to handle manifest files](https://monokle.io/) - for handling large data type files
  
