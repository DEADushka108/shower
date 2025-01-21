## Subresource Integrity

If you are loading Highlight.js via CDN you may wish to use [Subresource Integrity](https://developer.mozilla.org/en-US/docs/Web/Security/Subresource_Integrity) to guarantee that you are using a legimitate build of the library.

To do this you simply need to add the `integrity` attribute for each JavaScript file you download via CDN. These digests are used by the browser to confirm the files downloaded have not been modified.

```html
<script
  src="//cdnjs.cloudflare.com/ajax/libs/highlight.js/11.10.0/highlight.min.js"
  integrity="sha384-pGqTJHE/m20W4oDrfxTVzOutpMhjK3uP/0lReY0Jq/KInpuJSXUnk4WAYbciCLqT"></script>
<!-- including any other grammars you might need to load -->
<script
  src="//cdnjs.cloudflare.com/ajax/libs/highlight.js/11.10.0/languages/go.min.js"
  integrity="sha384-Mtb4EH3R9NMDME1sPQALOYR8KGqwrXAtmc6XGxDd0XaXB23irPKsuET0JjZt5utI"></script>
```

The full list of digests for every file can be found below.

### Digests

```
sha384-no5/zgQGupzPFGWV8VpJzfQau5/GI2v5b7I45l6nKc8gMOxzBHfgyxNdjQEnmW94 /es/languages/bash.js
sha384-u2nRnIxVxHkjnpxFScw/XgxNVuLz4dXXiT56xbp+Kk2b8AuStNgggHNpM9HO569A /es/languages/bash.min.js
sha384-LWvgGWXmngclEsDJmF3D0r9QTsAdIW8nZici4I4If/aw3c6268PitG+PNPAlVMFV /es/languages/csp.js
sha384-h92gzO66Hk1++bH+fXGmNay2Yf9WBsijCsnwubxdSE86gVf6UMC3drQ5VDjZaoaK /es/languages/csp.min.js
sha384-+9dzNYaLHp3OPspFCOJGrEwfiOV3yqeD/atUDYVt9zKUJ8IW2QxffCT2LfmGfwfW /es/languages/css.js
sha384-G44u1/pUATC8754FIKYqkCxCl9AQYnspnFxzuR3RB1YVnTvqOEofqvZNQMUWcY/1 /es/languages/css.min.js
sha384-yIW2CKaxiozMCGVe7a2RX90kdUjP0h2gALuNlfKbojKpQn1OmMQLGO7BOqhncFO6 /es/languages/http.js
sha384-j+2AgmE+4SlZjmviwPvbGypcb9BQNHQj043l9Bb3F2fnlusdNxxA5/INHsOrSE6g /es/languages/http.min.js
sha384-oQpcUGMBf+VDTHOLQ1uhPp1FgNBo0OZc9gbXGuVFwAogHlkh/Iw6cvKKgcgCQkmV /es/languages/javascript.js
sha384-3T8DJ91yCa1//uY9h8Bo4QLrgEtbz4ILN2x9kSM4QWX9/1kKu6UXC3RAbVQV85UQ /es/languages/javascript.min.js
sha384-R87hRh4kF8+iz2sB6FvLrfR0XZBohjFXeJKIXld1Eji2UVi+M2+OIgJKma/9Ko6u /es/languages/json.js
sha384-QFDPNpqtrgZCuAr70TZJFM4VCY+xNnyGKwJw2EsWIBJOVcWAns9PHcLzecyDVv+x /es/languages/json.min.js
sha384-BlC0mPZAwpk9QZaocgajHbYH8yYkOUZrDKpeaPBeCGrQfQ6eTZXyInS411HpGnO0 /es/languages/less.js
sha384-vmEaRQjBedDEQk0PmHXdDeC6kbUsP+AhxtGkI2jQ/VdSRZ9ndnDOBUuxp+cZ7pQV /es/languages/less.min.js
sha384-kcAcxYNWYVMr2nwgsILhFHZH+OkRjbK6xazY53sIcW9bta3onTtDBKug0swjsiMC /es/languages/scss.js
sha384-mlx1v98SAsuX2QnqD9+dsXOfilvT7QQjfyOD3HTrvA4TXsxV4yjW/+TqhUADUuOH /es/languages/scss.min.js
sha384-cu+ZTiz+DPlJzlpOCZzjhzj/sZd/xzvbWzjBP9QALEVkQaYwToO+oepMjwImUu+G /es/languages/stylus.js
sha384-p/nPinGn5chrt4cTKyQIBe6+Mq3I9wWfqtxG1zDeE1MFRpZgR5u7OMwne2uePVM2 /es/languages/stylus.min.js
sha384-BcyijKQAe0oJGoEBf0y/+dTJjKiy4bIAVdjreJw+MiOkPgCEjM/2FY2+W7K6tcEZ /es/languages/typescript.js
sha384-Mfjt0R07QBpLXhGWeCetLw7s2mTQSoXmcyYnfsSNq4V4YG3FwayBjxod9MxjSB1x /es/languages/typescript.min.js
sha384-TOvJ6ng9+2cEdYIo8UmcklrWBDxDmcyIc8eZ9tntvTcornli0usS+D1YJKmhMdU5 /es/languages/wasm.js
sha384-tu9x6stUNSb4pXeVRKavZtTp8ha5aQOjCp464ykdPSuI1BMHmN/07U/iqeaoKLgE /es/languages/wasm.min.js
sha384-Tdx2DY9ZTHx3KhVXYqOVKx3q1zOboDGlTTv8sgMlER8y4WETtqL+C4VQ7B4A0OGq /es/languages/xml.js
sha384-n9ZezaAVj8pK1BIFZQxmC1BM9yGuBNRgvsOxHMHPCXzqYd1gSYIu9KjgGEm8K57w /es/languages/xml.min.js
sha384-4SbTAv3AX2fuPCpSv6HW3p07YgA7hFfcwG2zJHtYv0ATIt1juD3IXj2NSYwTeIpm /languages/bash.js
sha384-83HvQQdGTWqnRLmgm19NjCb1+/awKJGytUX9sm3HJb2ddZ9Fs1Bst2bZogFjt9rr /languages/bash.min.js
sha384-gf4BcDpEnRsigTWjrncudvt6aXYYJuPqHO28JCgKNG5BtKKPR3YIU7M4X77LG/hG /languages/csp.js
sha384-GfsA+L6x4v9I1iiHCTfElgEMXs4tsXCw+gC+bC89n7nSXfUEfNemTt48EJD4jndY /languages/csp.min.js
sha384-h6xPJgkyvp13tIs697wZHjCH20tW1aJOrvnAKiZZiATSWZp0lyLB4bAdsEhWUSze /languages/css.js
sha384-+MO3D3y/aZzZq7QMAAA5KiuAcqBZivJHFmVUXfwdBoLxEXeGTeQGsNMll4fpnegg /languages/css.min.js
sha384-5njNAV6cayF+v1sc70/t3BTkztvcp8TZ61d65U8YUQuXJ45PIrhcgNfccRMd9JsI /languages/http.js
sha384-ubRntct0s40ZDtDRLkxA3/xYX51o5yC2U8SKlky8dhIRsjSnvZiUKLhz0gNTewno /languages/http.min.js
sha384-p/utwvqrRVOLlz0BjJ0BCGCb2liTDipfz47/QmGXz9hoPIjCKYEgmYUC30VmGgZy /languages/javascript.js
sha384-L/XmDiyusXomLRGcRmcBpPlboRFjpQNV747OJvg+sEOpgGYvUsNwcC4JLNQ2dI6O /languages/javascript.min.js
sha384-psmmPlbfEWGyvRapexDqkVTgNz7Y1xvlGdLNWQSafI4GFQYFDXPZxVXH1laU4n6l /languages/json.js
sha384-Bb6DhE3tUpBROwypL78TbhRUs9QbCt2GxcxVSYglt2l3MefrYkm4CfwjfWhRfQaX /languages/json.min.js
sha384-zlcx7qQtpp4cqCCPEDhWKvb3lEbhomD5HTubdLR78S/3AQBJGkHiT6LGziV0f4yH /languages/less.js
sha384-NZS9QHMmwN86GbNpIvGs4HOB2EzfqPjhIHqZviwZIw1HLumSMRnl4X/OIgpyP0+K /languages/less.min.js
sha384-1MNX8RDXroN7D+Jeq9f6EysUNAuhuQMq32wKcGB5yEDEJalUxEoSjfRVJhF0+YV6 /languages/scss.js
sha384-7CdPzO1jMDolQK+LCRlGiW1Oka6fSiQdIiqfTvHeBk2Hm2iYNoqMn60aJ9HdKkjb /languages/scss.min.js
sha384-0Yy/cZlbG78zeysOAMDd9OMKj8FrGaVfg/IH9zKh0JCBGMW0gabvTIAtdif4HpSh /languages/stylus.js
sha384-MoaYmkURrT/giCrgWXgBEOOXP+nEFtMKjRY2XIzWehdGT2GN73w+dTvyP+jZhEZL /languages/stylus.min.js
sha384-4q0Mj1AHSvVdgi6nXDGdkiHZQcme/PcCE+MvwCvnAIZSjhJfk3UpjJU2nn2eImWz /languages/typescript.js
sha384-rfwxAwuWzb2XdSU7HN3IhrSyCq96Nj4p1ZYPCNAGbqtnPsaWl8d5eSypxPbW6alT /languages/typescript.min.js
sha384-7+RHZQJsgiohPfYs4xGnVLR6bKm1cnz7rvB7mXEb2btmiWhSNq1cuTJsQWK9Ut8w /languages/wasm.js
sha384-TTxGby06lDIEB1Y6l2/Hd2VJbewWQSCESXUcDWC24gJN0IiptruI6DE1l5+w4Qzh /languages/wasm.min.js
sha384-QAL2h4IMgQaJUJjUy0dSWdAut7o/A272ai8qOsJ8SSm9KMxkdLgH7oGfLGft/EJ0 /languages/xml.js
sha384-CN3No+n1UZXCFYyl+ge5yAPGTNGuH23BdIsFJxntDmEYL94AmoZlNBHGSdjVSjKG /languages/xml.min.js
sha384-bZjHzQ9aUjnAjAa8eDUt5DwA8euNS4MrFqlvdFiMbJoLCvoS6hgwQplX7rGWapsl /highlight.js
sha384-XcaP47KDfNUhN9HCN0BIX3BfIVWP5BA9/jNtQzPWCFyn807h9HCHW6jVJhk683eI /highlight.min.js
```

