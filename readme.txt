=== Kblog Include ===

Contributors: philliplord
Tags: res-comms, scholar, academic, science
Requires at least: 3.0
Tested up to: 3.6.1
Stable Tag: 0.1
License: GPLv3.0

Transcludes content from arXiv and other academic repositories.

== Description ==

With this plugin you can include content from arXiv or other academic
repositories in your blog post. For example, if placing

    [kblog-inc server="arxiv"]1303.0213[/kblog-inc]

in your blog post, the abstract of this article will be include at this point
in text. Additionally, the title will be set to the title of the article ("The
semantic web takes wing" in this case). Finally, if you have use
[http://wordpress.org/plugins/kblog-metadata/](kblog-metadata), the authors,
and date will be set appropriately also.

It is possible to add additional material to the post as normal; for example,
with my
[http://www.russet.org.uk/blog/category/all/professional/science/papers](papers),
I add a plain English summary, and where the authors allow, I also add the
reviews; an example can be seen for the above
[http://www.russet.org.uk/blog/2366]([paper).

Kblog-include uses OAI-PHM to harvest the metadata that is displays; as this
is a standard, it should mean that kblog-include can transclude from any
repository that supports this standard. In practice, unfortunately, different
repositories use the tags in different ways. Currently, kblog-include supports
http://arxiv.org, the [http://eprint.ncl.ac.uk](Newcastle University) eprints
server, and [http://greycite.knowledgeblog.org](Greycite). For example:

   [kblog-inc server="eprint.ncl.ac.uk"]193637[/kblog-inc]

Shows one of my papers.

I am open to requests for new servers, ideally, via
[https://github.com/phillord/kblog-include](pull request), or email otherwise.


== Installation ==

1. Unzip the downloaded .zip archive to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress

== Upgrade Notice ==

0.1 Initial Release

== Changelog ==

0.1 Initial Release
