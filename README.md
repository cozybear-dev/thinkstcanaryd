# thinkstcanaryd

Simple setup for private use of honeypots.

Used with Zapier webhook, that escalates to Pushover to mobile phone.

Evaluate the config and change accordingly!

Always change default values, to avoid fingerprinting.

Also always test the alerting. Different services act differently. Most services will only alert, if actual data is send - whilst you perhaps want to know when any request is send. I personally use a combination of services, that cover both. To trigger on anything, use the tcp_banner option.
