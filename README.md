Monitoring Solr with Opsview
============================

This repository contains an Opsview (<http://www.opsview.com>) plugin written in Perl for monitoring Solr (<http://lucene.apache.org/solr/>).

See <http://leanjavaengineering.wordpress.com/2011/12/07/monitoring-apache-solr/> for more information.

Brief instructions
------------------
1. Copy *check_solr* to */usr/local/nagios/libexec*
2. Ensure that *check_solr* is executable (using `chmod +x`)
3. You will need to have the *XML::XPath* CPAN module (`sudo cpan -i XML::XPath`)
4. Look at the usage instructions (`./check_solr -h` or look at the Plugin help within Opsview)
