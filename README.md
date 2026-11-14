# jochenseiler-byte.github.io

GitHub Pages site that hosts the Tesla Fleet API public key for Home Assistant.

The key is served at:

https://jochenseiler-byte.github.io/.well-known/appspecific/com.tesla.3p.public-key.pem

`.nojekyll` is in the repo root so GitHub Pages publishes the `.well-known` folder. Jekyll skips directories whose names start with a dot unless that file is present.

The public key file is added separately. Never commit a private key or other secret.
