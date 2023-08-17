# JmeterScripts
here I collect my scripts from JMeter.

1. buyProduct.jmx - end-toend flow script from login to adding the product to the cart and sending it to the buyer.
Each request uses random thinking time, assertions, Random CVS data plugin.
Сategory and product are selected randomly. Regex extractors are used to select from category and product.

2. userRegister.jmx - automatic generation of data for registering a new user, registration of a new user,
   automatic generation of data for changing data in an account, adding products to the wish list randomly using regex,
   while controller, beanshell sampler for counter.

3. ConcurrencyThread500.jmx -stress testing buyProduct.jmx scenario. 500VU, using Concurrency thread group plugin   
