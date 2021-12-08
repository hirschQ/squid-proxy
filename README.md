# squid-proxy

 create not-to-cache-site

#add to squid.conf
acl NO-CACHE-SITES dstdomain "/etc/squid/not-to-cache-sites.txt"
no_cache deny NO-CACHE-SITES

#####paste my collection to your txt.
