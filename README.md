# Shopify-Script-For-Discount-on-Prepaid-Order
Shopify Script For Discount on Prepaid Order &amp; Increase Conversion

There are certain types of tricks which can increase conversion on Shopify store and marchants can get good advantage from it. 
On of most popular and used worldwidely is <b>Shopify Script For Discount</b> applicable only on <b>Prepaid Orders</b> 

In this section, I will explain you given below points.
1. What is Shopify scripts?
2. How to use Shopify scripts?
3. How to implement these scripts? 
and related topics of Shopify scripts

Before proceediing next, I must like to clear that Shopify Scripts can be only used in Shopify Plus/ Gold Plans.

<h2>What is Shopify scripts?</h2>
<p>Shopify scripts are written in Ruby which gave us permission to create new users experience. Using <b>Line item, Shipping Method & Payment Methods</b> scripts you can implement custom logic and tailor the user experience during a user’s checkout experience. Scripts are enabled on a store’s checkout by using the Script Editor app.</p>

<h2>How to use Shopify scripts?</h2>
<p>Use the <b>Script Editor App</b> to create, edit, test, and publish your scripts.</p>
<p>Only one script per script type can be published at one time. For example, you can publish a line items script and a shipping rates script, but you can't publish two line items scripts at the same time.</p>

<h2>How to implement these scripts? </h2>
<ul>
<li>Open the Script Editor. The Scripts overview page shows a list of scripts for your store.</li>
<li>Click Create script to begin creating a new script.</li>
<li>Select script template.</li>
<li>In the Title box, enter a name for the script. Use a descriptive name so you can tell what the script does at a glance.</li>
<li>Click Code to open the Ruby source code console.</li>
<li>Click Run script to run the script.</li>
<li>click Save and publish to create and publish the script.</li>
</ul>

Given below steps you need to follow to implement Shopify script for prepaid order discount.
<ul>
<li>Install Shopify script app (https://apps.shopify.com/script-editor)</li>
  <li>Create new line item script and copy code from this <a href="https://github.com/kirpalsingh17/Shopify-Script-For-Discount-on-Prepaid-Order/blob/master/lineitem_discount.rb">file.</a> </li>
<li>Copy this code to your <a href="https://github.com/kirpalsingh17/Shopify-Script-For-Discount-on-Prepaid-Order/blob/master/update_code_checkout.liquid">checkout.liquid</a> file in the layout folder</li>
<li>Create new javascript file named as carrie.checkout-script.js in the assets folder.</li>
<li>Copy this javascript code in <a href="https://github.com/kirpalsingh17/Shopify-Script-For-Discount-on-Prepaid-Order/blob/master/carrie.checkout-script.js">carrie.checkout-script.js</a> file</li>
</ul>

<h2>Major file to amendment</h2>
For changes on price according to discount based.
<pre>carrie.checkout-script.js</pre>

Shopify Ruby script code to apply discount on products.
<pre>lineitem_discount.rb</pre>

Updated checkout.liquid to applicable for prepaid orders.
<pre>update_code_checkout.liquid</pre>
