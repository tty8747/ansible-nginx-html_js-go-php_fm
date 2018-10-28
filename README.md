# ansible-nginx-html_js-go-php_fm
1. ansible -i inventory/dev all -m "raw" -a "test -x /usr/bin/python || echo '--- PYTHON NOT INSTALLED ---'"
