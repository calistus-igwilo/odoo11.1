# odoo11.1
Odoo11 with pandas, xlsxwriter, xlrd, inflect and request[security]

# Usage
Download the dockerfile, entrypoint.sh, and odoo.conf to a local folder
From the folder path, build odoo11 image with the command:
# docker build --tag odoo11 .
The resulting image will have pandas, xlswriter, xlrd, inflect etc to support custom modules that requires them
