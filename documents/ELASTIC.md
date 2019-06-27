### Elastic Stack Configuration

Navigate to Kibana and login with the account you setup during install.

On the left at the very bottom is a gear icon. This is the Management Icon if you hover over it. Click it.

![Welcome Screen](../assets/elastic/elastic1.png)

Under Kibana on the left side, click "Index Management". This is NOT the one under Elasticsearch.

![Welcome Screen](../assets/elastic/elastic2.png)

Click the X in the webpage to close the pane titled "About Index Patterns".

![Welcome Screen](../assets/elastic/elastic4.png)

Now click the "Create index pattern" button.

![Welcome Screen](../assets/elastic/elastic3.png)

In the Index Pattern box, type "logstash-\*" and click Next Step.

![Welcome Screen](../assets/elastic/elastic5.png)

Select "@timestamp" from the Time Filter field name and click the "Create index pattern" button.

![Welcome Screen](../assets/elastic/elastic6.png)

Congratulations. You're now ready to search your data in Kibana.
