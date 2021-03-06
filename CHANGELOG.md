|Date      |Issue |Description                                                                                              |
|----------|------|---------------------------------------------------------------------------------------------------------|
|2016/12/13|      |Release 0.0.10                                                                                           |
|2016/12/11|48    |Use the new Pure Ruby NATS gem and remove EM                                                             |
|2016/11/19|55    |When root consult Puppet configuration to find the SSL dir, make ssl dir configurable                    |
|2016/11/19|68    |Update eventmachine to 1.2.1 and install that by default, improve logging of EM mode and version         |
|2016/11/01|      |Release 0.0.9                                                                                            |
|2016/10/20|61    |Support PQL queries on the CLI for node discovery                                                        |
|2016/10/07|59    |Reqiure missing resolv dependency                                                                        |
|2016/09/12|56    |Filter out deactivated nodes from discovery results                                                      |
|2016/08/22|35    |Simplify facts queries using latest PuppetDB PQL                                                         |
|2016/08/20|52    |Release 0.0.8                                                                                            |
|2016/08/19|49    |Set the connection name                                                                                  |
|2016/08/19|42    |Support NATS gem 0.8.0 and log connected NATS brokers                                                    |
|2016/08/13|      |Release 0.0.7                                                                                            |
|2016/08/13|45    |Fix calling facter on windows                                                                            |
|2016/08/11|      |Release 0.0.6                                                                                            |
|2016/08/10|34    |Correctly declare Apache-2.0 licence                                                                     |
|2016/08/10|37    |Improve errors when a empty site catalog is found                                                        |
|2016/08/01|      |Release 0.0.5                                                                                            |
|2016/08/01|29    |Fix discovery of rpcutil and subclasses                                                                  |
|2016/08/01|      |Release 0.0.4                                                                                            |
|2016/08/01|27    |Install client files only on clients and not everywhere                                                  |
|2016/08/01|27    |Improve discovery of agents in cases where there are client only installs                                |
|2016/07/29|22    |Improve handling of errors from the nodes                                                                |
|2016/07/26|20    |Fix incorrect module data                                                                                |
|2016/07/23|10    |Import mcollective-connector-nats                                                                        |
|2016/07/23|8     |Import mcollective-discovery-puppetdb as `choria` discovery provider                                     |
|2016/07/23|3     |Import mcollective-security-puppet as `choria` security provider                                         |
|2016/07/22|4     |Move orchestrator into a class of its own, add tests                                                     |
|2016/07/22|1     |Detect cyclic catalogs                                                                                   |
