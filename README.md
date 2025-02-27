![PyPI Downloads](https://static.pepy.tech/badge/mapper-parser)

<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width=330 height=86 src="//music.163.com/outchain/player?type=2&id=2678085008&auto=1&height=66"></iframe>

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

