# SuperKube

<p align="center">
<img src="https://superkube.net/images/superkube.svg" width="150" alt="SuperKube">
</p>

SuperKube is an open source command line tool for Kubernetes cluster management written in Go.
SuperKube can be run as a stand-alone utility, but really shines when
installed as a kubectl plug-in.

SuperKube can analyze and compare the performance and cost of your Kubernetes cluster running with your current provider and compare this with another provider. Out-of-the-box SuperKube supports Amazon, Google and Microsoft. Plugins for other providers are easy to write.
Performance and cost analyses are presented in simple tables with easy-to-understand key performance indicators.

If your cluster can run faster or cheaper with a different provider, SuperKube can transfer your entire cluster from one provider to another.
If you use the SuperKube ingress, your cluster's external IP addresses are preserved when moving between providers.

SuperKube kan also provision new clusters for you and backup and restore your clusters.

STATUS: SuperKube is currently under development, source code and binaries will be available here. To get a sense of the basic ideas, we have hacked together a simple technology preview that runs in a web browser. Check it out at [https://superkube.net](https://superkube.net).

## Credits
Thanks to [https://root.vc](https://root.vc) - we shamelessly copied the code from their website for the technology preview.