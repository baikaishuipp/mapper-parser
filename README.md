
### Description
Mybatis mapper xml file parser in pure python, get result contains:

- namespace
- resultMaps: contains start_line, end_line, content
- sqls: contains start_line, end_line, content
- statements: select/update/insert/delete statement, contains:start_line, end_line, content, statement_tag, result_map, include_sql

#### Installation
```
pip install mapper-parser
```

#### Instructions
```
from mapper_parser import mapper_parser

mapper_parser.parse(xml_filepath)
```

