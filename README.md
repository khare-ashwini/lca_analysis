## LCA Applications analysis
Load `h1b.ipynb` for basic statistics on LCA Applications submitted for FY2016. Applications for Visas like H1B, H1-B1, E-3 and PERM require a LCA application, which is disclosed periodically by OFLC.  Related [blogpost](http://ashwinikhare.in/tech-firms-guest-visa/)

### Data
To get the data:
- Download [PERM](https://www.foreignlaborcert.doleta.gov/docs/py2015q4/PERM_Disclosure_Data_FY15_Q4.xlsx) and [LCA](https://www.foreignlaborcert.doleta.gov/docs/py2015q4/H-1B_Disclosure_Data_FY15_Q4.xlsx) from OFLC website 
- Using [xlsx2csv](https://github.com/dilshod/xlsx2csv), convert `*.xlsx` to `*.csx`. Command :
```
xlsx2csv *.xlsx > *.csv
```
- Update data links in ipynb

## LICENSE
MIT
