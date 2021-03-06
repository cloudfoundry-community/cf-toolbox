Cloud Foundry Toolbox
=====================

The https://cf-toolbox.org site is a community showcase and discovery site. Find all the wonderful tools, apps, service brokers, plugins and more by other Cloud Foundry users.

Forking/Pull Requests
---------------------

Pull requests are encouraged! Add new wrappers or more tags to existing ones.

1.	`bundle install`
2.	Add your new data to `data.json`
3.	Preview your changes with `middleman` and `rake open`
4.	Submit a pull request
5.	Pull request will be merged and deployed

Ask nicely and you will be given Merge & Deploy permissions.

Deployment
----------

This site can be deployed to any Cloud Foundry. It uses the [staticfile-buildpack](https://github.com/cloudfoundry-incubator/staticfile-buildpack) to host the static files generated by [middleman](https://middlemanapp.com/).

To re-build the static site and push to Cloud Foundry:

```
rake push
```
