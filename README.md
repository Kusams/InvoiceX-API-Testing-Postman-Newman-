
# InvoiceX – API Testing with Postman/Newman

## Run
newman run collections/invoicex.postman_collection.json \
  -e collections/invoicex.postman_environment.json \
  -r cli,html --reporter-html-export reports/report.html
