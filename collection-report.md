# Code Index - Bblueye

## Collection Report
- **仓库**: [collection-report](https://github.com/Bblueye/collection-report)
- **描述**: 每日 Collection 报表生成器 - 从数据库获取 Actual/Forecast 数据，填充 Excel 模板，生成 HTML 报表，发送邮件通知
- **语言**: Python
- **主要模块**: 
  - `CollectionReport.py` - 主程序
  - `include/cls_credit.py` - 数据库数据获取
  - `include/cls_mssql.py` - SQL Server 连接器
  - `include/cls_email.py` - 邮件发送
  - `include/cls_china_holiday.py` - 中国节假日判断
- **技术栈**: Python, MSSQL, openpyxl, PyInstaller
