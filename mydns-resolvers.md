# mydns-resolvers

This is a list of custom DNS resolvers supporting DNSCrypt and DNS-over-HTTP2 protocols.

To use this list, add this to the `[sources]` section of your `dnscrypt-proxy.toml` configuration file:

    [sources.'mydns']
    urls = ['https://raw.githubusercontent.com/trypophob1a/resolvers/main/mydns-resolvers.md']
    cache_file = 'mydns-resolvers.md'
    minisign_key = 'RWRSfNKI1Gr9mhT2TDYyEpyItIfw1gbhKpPAiENhi1pWe0UskWnE1byp'
    refresh_delay = 72
    prefix = ''

--
## mydns
Custom DoH resolver with IPv4 support.
Homepage: https://mydoh-production.up.railway.app/dns-query
sdns://AgAAAAAAAAAAAAAfbXlkb2gtcHJvZHVjdGlvbi51cC5yYWlsd2F5LmFwcAovZG5zLXF1ZXJ5
