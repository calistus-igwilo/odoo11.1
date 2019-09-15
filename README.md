# odoo11.1
Odoo11 dockerfile with extra packages: pandas, xlsxwriter, xlrd, inflect and request[security]

# Usage
Download the dockerfile, entrypoint.sh, and odoo.conf to a local folder
From the local folder path, build odoo11 image with the command:
# docker build --tag odoo11 .
The resulting image will have pandas, xlswriter, xlrd, inflect etc to support custom modules that requires them

Note: If error occurs in the build process, check to make sure that entrypoint.sh and odoo.conf files are present in the local folder
