# Workshops

This document will include resources that are used for our workshops

## Workshop 1 - Datasciense with clojure
### agenda

1. Planning our next meetings
2. Learning the library tech

### Resources

[A study on Regression applied to the Ames dataset](https://github.com/cnuernber/ames-house-prices/blob/master/src/clj_ml_wkg/ames_house_prices.clj)

[Library to encapsulate a few core concepts of techascent system](https://github.com/techascent/tech.ml)

### Summary

## Workshop 2 - Web development with clojure


####Tutorial - reagent 

(web with clojure script and reagent)[https://www.youtube.com/watch?v=wq6ctyZBb0A]


#### devtools dirac

install dirac on chrom to get debuging tools in browser

https://github.com/binaryage/dirac

#### Static App - reagent

lein new reagent-frontend static-app

##### Tasks

1. Add a list of items to home page using [:ul [:li "list item 1"]]
2. Add a form to the main page 
3. Add a field with on-change method. (see here)[https://stackoverflow.com/questions/40383392/clojurescript-placeholder-in-text-box]
4. add bootstrap (datepicker) [https://github.com/reagent-project/reagent-cookbook/tree/master/recipes/bootstrap-datepicker]



#### client-server app

lein new reagent client-server
##### Tasks

1. add a page to the router
2. Add a page to the server
3. add a form with a name and email and a post operation
4. write a post handler on the server 


#### (re-frame) [https://github.com/Day8/re-frame]

re-frame is a framework over reagent

We are not sure we are going to use it but it is important to know it exisits and the problem it is trying to solve


##### re-com(re-com) [https://github.com/Day8/re-com]


lein new re-frame lion +re-com



