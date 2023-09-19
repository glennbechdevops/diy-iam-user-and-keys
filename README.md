# DIY LAB-  AWS IAM, brukere og nøkler 
Hensikten med denne øvingen er at du skal bli kjent med AWS IAM og hvordan du finner din egen IAM bruker, lager nye nøkler.
Du skal også bli kjent med AWS CLI ved å installere det på egen maskin, og konfigurere nøkler. 

## Installer AWS CLI på din maskin

* https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html

## Lag IAM nøkler i AWS kontoen din 

* AWS pålogging https://244530008913.signin.aws.amazon.com/console
* Gå til IAM tjenesten i IAM miljøet, finn brukeren din og lag nøkler 

## Konfigurer AWS CLI 

Kjør ```aws configure``` på maskinen med nøklene dine, bruk ```eu-west-1``` som region,  og se at du for eksempel får lov til å gjøre en kommando 
som ```aws s3 ls``` for å liste S3 buckets

