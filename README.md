# Union.m
mkdir -p ceremony &amp;&amp; docker pull ghcr.io/unionlabs/union/mpc-client:v1.2 &amp;&amp; docker run -v $(pwd)/ceremony:/ceremony -w /ceremony -p 4919:4919 --rm -it ghcr.io/unionlabs/union/mpc-client:v1.2
mkdir -p ceremony && docker pull ghcr.io/unionlabs/union/mpc-client:v1.2 && docker run -v $(pwd)/ceremony:/ceremony -w /ceremony -p 4919:4919 --rm -it ghcr.io/unionlabs/union/mpc-client:v1.2
