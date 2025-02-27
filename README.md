![PyPI Downloads](https://static.pepy.tech/badge/mapper-parser)

<audio controls>
  <source src="https://music.163.com/outchain/player?type=2&id=2678085008&auto=1&height=32" type="audio/mp3">
  Your browser does not support the audio element.
</audio>

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

