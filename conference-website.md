# Creating a Conference Website

The ACMA has a permanent web presence at <https://computermusic.org.au>

Each year's ACMC organisers are responsible for creating their own conference website which is used for communicating submission information, the conference schedule and proceedings.

Creating a website doesn't have to be terribly difficult or expensive (as little as 12AUD to just buy a domain name). Here's some options and examples.

## 1. Jekyll and Github Pages.

The lowest cost way to do this is to create a website with [Jekyll and Github Pages](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll). 

The idea is that you write the website content (mostly) in Markdown and use a Jekyll theme to provide a format and layout for most of the pages. This is not terribly hard to figure out and the ACMCA committee members can provide some help getting started.

When you create a website this way, the hosting is free (provided by <https://github.com>), but you need to buy a domain name separately. E.g., the ACMC organisers can purchase a domain name for that year's conference (e.g., <https://acmc2020.com>).

You can also use other static site generators, e.g., Hugo, which will have a similar process.

## 2. MiniConf annd Github Pages

In 2020, we hosted the conference website using a system called "MiniConf": <https://github.com/Mini-Conf/Mini-Conf>

(You can still see the website here: <https://acmc2020.com>).

This is similar to the Jekyll / Github Pages option above, but required a bit more coding (in Python) to get it to work properly. The advantage with miniconf was the ability to display information about each presenter / paper / performance and with a very clear interface: <https://acmc2020.com/papers.html?filter=keywords>

## 3. Wordpress

Using a wordpress account is a good way to spin up a wordpress site quickly (<https://wordpress.com/>. The minimum cost is about 60AUD for a year of service (this includes a domain name).

Using wordpress won't let you make a nice interface for a schedule or individual papers as in the above options, but if you just want to have nicely set up pages quickly, it's a decent optionn.

You can run into trouble at the end of this year as it's a bit tricky to export a wordpress site for archive.

## After the conference

We'd like to be able to archive old conference websites for posterity. With 1 and 2 above, this is pretty easy (we just move the conference git repository to our ACMA organisation account). Option 3 makes this a bit harder, but still good to remember to do it.

We don't suggest that conference organisers pay for a domain name / hosting forever, better to just keep the domain as a temporary address for 1-2 years.
