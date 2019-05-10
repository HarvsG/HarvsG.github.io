# www.codingdoctor.co.uk
A Jekyll website
How I made this website - a note to self
- I registered the codingdoctor.co.uk domain with Namecheap and moved the DNS servers to Digital ocean
- I did a manual fork of https://github.com/barryclark/jekyll-now and made edits to `/_config.yml`
- I edited `/_posts/` and `/_layouts/default.html`
- See commits for more edits
- I used this guide to configure the custom domain https://help.github.com/en/articles/quick-start-setting-up-a-custom-domain
  - I used the `www.` subdomain and set up CNAME on digitalocean
- I then used MX forwarding on https://improvmx.com/ and digital ocean to forward doctor@codingdoctor.co.uk to one of my personal addresses
