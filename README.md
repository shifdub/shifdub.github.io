
## Introduction

I'm Interested in java development and I am currently attending the deep Dive Coding Bootcamp. My goal is to finish this class and learn alot.

## Current Projects

> * [Hello World: Java console application](https://github.com/shifdub/hello-world)
> * [Hello World: Android app](https://github.com/shifdub/android-hello-world)

## Links

> * [Facebook](https://www.facebook.com/shifdub)


//opening paragraph

### Recently updated repositories

{% assign public_repositories = site.github.public_repositories | where: 'fork', false | sort: 'updated_at' | reverse %}
{% for repo in public_repositories limit: 10 %}
* [{{reo.name}}]({{ repo.html_url }})
{% endfor %}


//##links section


