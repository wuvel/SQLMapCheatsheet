# SQLMapCheatsheet

## Tamper
  **All scripts**
  ```
  --tamper=apostrophemask,apostrophenullencode,appendnullbyte,base64encode,between,bluecoat,chardoubleencode,charencode,charunicodeencode,concat2concatws,equaltolike,greatest,halfversionedmorekeywords,ifnull2ifisnull,modsecurityversioned,modsecurityzeroversioned,multiplespaces,nonrecursivereplacement,percentage,randomcase,randomcomments,securesphere,space2comment,space2dash,space2hash,space2morehash,space2mssqlblank,space2mssqlhash,space2mysqlblank,space2mysqldash,space2plus,space2randomblank,sp_password,unionalltounion,unmagicquotes,versionedkeywords,versionedmorekeywords
  ```

  **General scripts**
  ```
  --tamper=apostrophemask,apostrophenullencode,base64encode,between,chardoubleencode,charencode,charunicodeencode,equaltolike,greatest,ifnull2ifisnull,multiplespaces,nonrecursivereplacement,percentage,randomcase,securesphere,space2comment,space2plus,space2randomblank,unionalltounion,unmagicquotes
  ```

  **Microsoft access**
  ```
  --tamper=between,bluecoat,charencode,charunicodeencode,concat2concatws,equaltolike,greatest,halfversionedmorekeywords,ifnull2ifisnull,modsecurityversioned,modsecurityzeroversioned,multiplespaces,nonrecursivereplacement,percentage,randomcase,securesphere,space2comment,space2hash,space2morehash,space2mysqldash,space2plus,space2randomblank,unionalltounion,unmagicquotes,versionedkeywords,versionedmorekeywords
  ```

  **Microsoft SQL Server**
  ```
  --tamper=between,charencode,charunicodeencode,equaltolike,greatest,multiplespaces,nonrecursivereplacement,percentage,randomcase,securesphere,sp_password,space2comment,space2dash,space2mssqlblank,space2mysqldash,space2plus,space2randomblank,unionalltounion,unmagicquotes
  ```

  **MySQL**
  ```
  --tamper=between,bluecoat,charencode,charunicodeencode,concat2concatws,equaltolike,greatest,halfversionedmorekeywords,ifnull2ifisnull,modsecurityversioned,modsecurityzeroversioned,multiplespaces,nonrecursivereplacement,percentage,randomcase,securesphere,space2comment,space2hash,space2morehash,space2mysqldash,space2plus,space2randomblank,unionalltounion,unmagicquotes,versionedkeywords,versionedmorekeywords,xforwardedfor
  ```

  **Oracle**
  ```
  --tamper=between,charencode,equaltolike,greatest,multiplespaces,nonrecursivereplacement,randomcase,securesphere,space2comment,space2plus,space2randomblank,unionalltounion,unmagicquotes,xforwardedfor
  ```

  **PostgreSQL**
  ```
  --tamper=between,charencode,charunicodeencode,equaltolike,greatest,multiplespaces,nonrecursivereplacement,percentage,randomcase,securesphere,space2comment,space2plus,space2randomblank,xforwardedfor
  ```

  **SAP MaxDB**
  ```
  --tamper=ifnull2ifisnull,nonrecursivereplacement,randomcase,securesphere,space2comment,space2plus,unionalltounion,unmagicquotes,xforwardedfor
  ```

  **SQLite**
  ```
  --tamper=ifnull2ifisnull,multiplespaces,nonrecursivereplacement,randomcase,securesphere,space2comment,space2dash,space2plus,unionalltounion,unmagicquotes,xforwardedfor
  ```
