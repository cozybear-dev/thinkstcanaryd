# thinkstcanaryd

Simple setup for private use of honeypots.

Used with Pipedream, that escalates to Pushover to mobile phone. Zapier/IFTT are no longer options for me, as you have to pay obscene amounts of money.

Evaluate the config and change accordingly!

Always change default values, to avoid fingerprinting.

Also always test the alerting. Different services act differently. Most services will only alert, if actual data is send - whilst you perhaps want to know when any request is send. I personally use a combination of services, that cover both. To trigger on anything, use the tcp_banner option.
