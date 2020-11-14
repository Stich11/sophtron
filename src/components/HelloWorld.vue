<template>
  <div>
    <p>
      <span style="color: rgb(159,194,132);">Sophtron</span>()
      <br />
      <span class="comment">
      // Easily connect financial data to your application
      </span>
    </p>
    <p>
      <span class="object-header">Available Data Sources</span> <span class="bracket">{</span>
        <br />
        <br />
        <span class="line">Bank.<span class="object-item">accounts</span></span>
        <span class="line">Credit Card.<span class="object-item">accounts</span></span>
        <span class="line">Investment.<span class="object-item">accounts</span></span>
        <span class="line">Insurance.<span class="object-item">accounts</span></span>
        <span class="line">Cell Phone.<span class="object-item">accounts</span></span>
        <span class="line">Electricity.<span class="object-item">accounts</span></span>
        <span class="line">Lending.<span class="object-item">accounts</span></span>
        <span class="line">Other.<span class="object-item">accounts</span></span>
      <span class="bracket">}</span>
    </p>
    <p class="comment">
     // You can build applications with permission from the user without permission from a competing financial institution 
    </p>
    <p>
      <span class="object-header">Available Data Fields</span> <span class="bracket">{</span>
        <br />
        <br />
        <span class="line">Bank Account.<span class="object-item-2">balance</span></span>
        <span class="line">Bank Account Owner.<span class="object-item-2">name</span></span>
        <span class="line">Bank Account Owner.<span class="object-item-2">address</span></span>
        <span class="line">Bank Account.<span class="object-item-2">number</span></span>
        <span class="line">Bank Transactions.<span class="object-item-2">4+ Years</span></span>
        <span class="line">Rewards Points()</span>
      <span class="bracket">}</span>
    </p>
    <p class="comment">
      // Sophtron uses Machine Learning to automatically fix connection issues without the need for human intervention keeping our uptime unmatched
    </p>
    <p>
      <span class="object-header">Supported Institutions By Country</span> <span class="bracket">{</span>
        <br />
        <br />
        <span class="line">United States(<span class="object-item-3">14321</span>)</span>
        <span class="line">Canada(<span class="object-item-3">1164</span>)</span>
        <span class="line">India(<span class="object-item-3">325</span>)</span>
        <span class="line">Other English(<span class="object-item-3">3256</span>)</span>
      <span class="bracket">}</span>
    </p>
    <p class="comment">
      // Our neural network adds new financial institutions automatically so Sophtron supports more data sources than our nearest two competitors combined
    </p>
    <p class="comment">
      // AI does the work of adding and maintaining connections so our fees are an order of magnitude less than Yodlee and Plaid
    </p>
    <p>
      <span class="object-header">Applications Using Sophtron</span> <span class="bracket">{</span>
        <br />
        <br />
        <span class="line">Accounting.<span class="object-item-2">software</span></span>
        <span class="line">Lending.<span class="object-item-2">services</span></span>
        <span class="line">Payments.<span class="object-item-2">processors</span></span>
        <span class="line">Banks()</span>
        <span class="line">Wealth.<span class="object-item-2">managers</span></span>
        <span class="line">Bill_Pay.<span class="object-item-2">processors</span></span>
      <span class="bracket">}</span>
    </p>
    <p class="comment">
      //  Onboard new wealth management customers by automatically downloading their financial balances
    </p>
    <p class="comment">
      //  Use bank transaction history to make smarter lending decisions
    </p>
    <p class="comment">
      // Display bank transactions within your application
    </p>
    <p class="comment">
      // Verify the users account and routing number to prevent payment failures due to typos
    </p>
    <p class="comment">
      // Verify a users identity to reduce fraud using their bank account, their cell phone account and their cell phone number
    </p>
    <p style="color: #ffe599; text-align: center;">
      *** Contact sales@sohptron.com for more information ***
    </p>
 
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style>
.line {
  display:block;
  text-indent:1em;
}
p {
  text-align: left;
  margin-left: 1em;
  color: white;
}
.comment {
  color: #00ffff;
}
.bracket {
  color: #674ea7;
}
.object-header {
  color: #f1c232;
}
.object-item {
  color: #e06666;
}
.object-item-2 {
  color: #c27ba0;
}
.object-item-3 {
  color: #cc4125;
}
</style>
