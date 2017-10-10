# Pharo ZeroConf

_Installation of software can be cumbersome especially when you have to download several components while making sure that they fit together at the same time. Would'nt it be better if I could run a simple command line script that fetches the correct versions for me? Exactly this is what Pharo ZeroConf tries to address._

Basically Pharo ZeroConf is a webpage located at [http://get.pharo.org](http://get.pharo.org) that you can use to easily script the installation of necessary Pharo components \(like the image file or the virtual machine\).

If you are on Linux you can easily run:

```
curl get.pharo.org | bash
```

or if _curl_ is not available

```
wget -O- get.pharo.org | bash
```

from the commandline to get the the latest Pharo release.

