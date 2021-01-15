# Parse and analyze voucher-pdfs from woocommerce using Python and Pandas
So, you recieved some pdfs with exports from the woocommerce voucher system and you need to extract some data...\
The need here was to analyze how much money was still in used, unused and expired giftcards.

- This is a jupter-notebook using Python 3.8 to parse a couple of these pdfs, with their own set of weirdness...
- It uses the ... java-based library for reading the pdf, and then passes the content into a pandas dataframe.
- We then analyze/crawl/parse the pandas dataframe to excract the correct data. 
- It generates some csv-reports based on classifications based on SKU-values.
