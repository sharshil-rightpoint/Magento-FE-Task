Setup into any Magento2 Project
-Clone the Repo
-Copy the RP folder from the REPO
-And paste inside your magento folder  app/code
    Run - Upgrade command
    Run - Deploy command
    Run - Cahce Clean
and add this path after your magneto main url - /offers/index/index   
i.e - mageno.test/offers/index/index


Task requirement

1. Create one AMD Module JS/Custom JS
2. Define that JS path in requirejs-config.JS
3. Call/Initiate that JS in offers.phtml
5. Pass the api url php variable to the JS which you created and get the data from the api 
6. And render all the products into this DOM which in the phtml file.
    <!-- <div class="offerproducts" id="offer-product"> -->
