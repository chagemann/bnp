---
layout: page
title: Contact
permalink: /contact/
---

Please contact me via <a href="mailto:{{ 'anne_harjes@yahoo.com' | encode_email }}?Subject=Contact via Bubbles and Paint">email</a> or <a href="tel:{{ '0413 914 978' | encode_email }}">phone</a> or complete the form below.

Location: Ashmore QLD 4214, Australia
<hr/>
 
&nbsp; 

<div id="formkeep-embed" data-formkeep-url="https://formkeep.com/p/3796c9879875fb662eba4acf7674e249?embedded=1"></div>

<script type="text/javascript" src="https://pym.nprapps.org/pym.v1.min.js"></script>
<script type="text/javascript" src="https://formkeep-production-herokuapp-com.global.ssl.fastly.net/formkeep-embed.js"></script>

<!-- Get notified when the form is submitted, add your own code below: -->
<script>
const formkeepEmbed = document.querySelector('#formkeep-embed')

formkeepEmbed.addEventListener('formkeep-embed:submitting', _event => {
  console.log('Submitting form...')
})

formkeepEmbed.addEventListener('formkeep-embed:submitted', _event => {
  console.log('Submitted form...')
})
</script>
