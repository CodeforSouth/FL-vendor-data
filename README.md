# FL-vendor-data
Repo for statewide vendor data challenge …

We'd like to know what everyone makes, even if it's just a list of links to other repos.
Feel free also to work in this repo within the folder for your city.

**THANKS!**
_______

## About the Florida Vendor Payments data challenge
A Statewide Challenge to make the state’s vendor payment data more easily digestible and meaningful to taxpayers and citizens of Florida by creating an interactive and/or visual tool of this data.

### About the Data
* Provides information about state disbursements to vendors/payees
* Data is posted as part of Transparency Florida: http://www.myfloridacfo.com/Transparency/  
  (data can be found under “State Payments” button on Transparency Florida main page)
* Main webpage for Vendor Payment data: http://flair.myfloridacfo.com/dispub2/cvphsrch.htm
* Searchable Database of these data available at: http://flair.dbf.state.fl.us/dispub2/newvpymt4.shtml

### Bulk Download
Bulk downloads of State Vendor Payments data available online for 6 state Fiscal Years (Fiscal Years 2009 – 2014): http://www.myfloridacfo.com/transparency/vendorpayments.aspx

NThe files are pipe-delimited, but for many of the 23,122,218 records this isn't consistent. Some vendor names have pipes in their names which can throw off parsing, and some of the fields extend into the next field, so appear with a / (slash) delimiter instead of a pipe; which also throws off parsing.

Contributor and Jacksonville Technology Wonk Brady Merkel has re-composed the input files which will import much easily to your favorite database engine.
Get the corrected files from DropBox here:
* FY2009.zip: https://www.dropbox.com/s/fxg9toow4o0xygf/FY2009.zip?dl=0
* FY2010.zip: https://www.dropbox.com/s/gp8led793s5pn6s/FY2010.zip?dl=0
* FY2011.zip: https://www.dropbox.com/s/vykgppvmcd8h53y/FY2011.zip?dl=0
* FY2012.zip: https://www.dropbox.com/s/7h8hvrtnq9naspd/FY2012.zip?dl=0
* FY2013.zip: https://www.dropbox.com/s/jj1pok4wxaz692j/FY2013.zip?dl=0
* FY2014.zip: https://www.dropbox.com/s/6pg3eoxye7z5kt2/FY2014.zip?dl=0

### What can be illustrated with this data?
Who we (the State of Florida) pay, for what, and how much.

You can Search vendor payments data by:

* Warrant No./ Invoice No.
* Date Range/ Fiscal Year
* Object Code Classification(s) 
* Vendor Name/ Number/ Type
* Minority Classification(s)
* Paying State Agency(s)
* Amount
* Location (address/ phone area code)

____

### Vendor data API via @becdar (Code for Fort Lauderdale)
https://github.com/becdar/payments-api
