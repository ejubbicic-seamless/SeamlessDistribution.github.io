---
layout: default
title: SEQR Integration Sign up
description: SEQR Integration Sign up
---

# Get login credentials

You need to [contact](/contact) Seamless to get reseller ID and password. With these you call the registerTerminal API request to receive a terminal ID. The terminal ID and password can then be used to make payment requests.



Example terminal context, that can be used before contacting us:
{% highlight python %}
context.initiatorPrincipalId.type = 'TERMINALID'
context.initiatorPrincipalId.id = '8609bf533abf4a20816e8bfe76639521'
context.password = 'N2YFUhKaB1ZSuVF'
{% endhighlight %}

Example shop/reseller context, that can be used before contacting us:
{% highlight python %}
context.initiatorPrincipalId.type = 'RESELLERUSER'
context.initiatorPrincipalId.id = 'public_test_shop'
context.initiatorPrincipalId.userId = '9900'
context.password = '1234'
{% endhighlight %}



