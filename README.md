# BorderPay.Io

<h4><a id="Installation_6"></a>Installation</h4>
<p>Employeeledger requires <a href="https://www.docker.com/">Docker</a> &amp; <a href="https://golang.org/">Go</a> to run.</p>
<h3><a id="Docker_10"></a>Docker</h3>
<pre><code class="language-sh">$ sudo apt install docker.io
$ sudo apt install docker-compose
</code></pre>
<h2><a id="Go_15"></a>Go</h2>
<h4><a id="Installation_16"></a>Installation</h4>
<pre><code class="language-sh">$ sudo apt-get update
$ sudo apt-get install golang-go
</code></pre>
<h4><a id="Set_your_Go_path_as_environmental_variable_21"></a>Set your Go path as environmental variable</h4>
<h6><a id="add_these_following_variable_into_the_profile_22"></a>add these following variable into the profile</h6>
<pre><code class="language-sh">$ <span class="hljs-built_in">export</span> GOPATH=<span class="hljs-variable">$HOME</span>/go
$ <span class="hljs-built_in">export</span> PATH=<span class="hljs-variable">$PATH</span>:/usr/<span class="hljs-built_in">local</span>/go/bin:<span class="hljs-variable">$GOPATH</span>/bin
</code></pre>
<h6><a id="then_27"></a>then</h6>
<pre><code class="language-sh">$ <span class="hljs-built_in">source</span> ~/.profile
$ go version
$ go version go1.<span class="hljs-number">11</span> linux/amd64
</code></pre>
<h3><a id="Build_Your_Network_34"></a>Build Your Network</h3>

### [[⬆]](#init) <a name='setup_all'>Set Up Details</a>

```
Working Dir : test-net
```

Install the hyperledger pre-requisites.

* [Getting Started](https://hyperledger-fabric.readthedocs.io/en/latest/getting_started.html)

First Install these dependencies. This includes ```git```, ```curl```, ```wget```, ```golang```,```docker``` & ```docker-compose```.
We assume that you will be using ```golang``` as the primary language for developing the chaincode.

* [Pre-requisite Installs]([https://hyperledger-fabric.readthedocs.io/en/release-2.0/prereqs.html](https://hyperledger-fabric.readthedocs.io/en/latest/prereqs.html])

Next we install the hyperledger binaries and the docker images.

* [Install Samples, Binaries and Docker Images]([(https://hyperledger-fabric.readthedocs.io/en/latest/install.html])

Check if the dependcies have been met. Shown below is an output for the versions installed in the setup. Setup the ```GOPATH``` appropriately.

* [Setting GOPATH](https://github.com/golang/go/wiki/SettingGOPATH)

* [USING GO11MODULE](https://dev.to/maelvls/why-is-go111module-everywhere-and-everything-about-go-modules-24k)

```bash
➜  ~ git --version
git version 2.20.1

➜  ~ go version
go version go1.12.10 linux/amd64

➜  ~ node -v
v12.13.1

➜  ~ npm -v
6.12.1

➜  ~ python --version
Python 2.7.17

➜  ~ python3 --version
Python 3.7.5

➜  ~ pip --version
pip 19.2.3 from /usr/local/lib/python2.7/dist-packages/pip (python 2.7)

➜  ~ pip3 --version
pip 18.1 from /usr/lib/python3/dist-packages/pip (python 3.7)

➜  ~ curl --version
curl 7.65.3 (x86_64-pc-linux-gnu) libcurl/7.65.3 OpenSSL/1.1.1c zlib/1.2.11 libidn2/2.2.0 libpsl/0.20.2 (+libidn2/2.0.5) libssh/0.9.0/openssl/zlib nghttp2/1.39.2 librtmp/2.3
Release-Date: 2019-07-19
Protocols: dict file ftp ftps gopher http https imap imaps ldap ldaps pop3 pop3s rtmp rtsp scp sftp smb smbs smtp smtps telnet tftp
Features: AsynchDNS GSS-API HTTP2 HTTPS-proxy IDN IPv6 Kerberos Largefile libz NTLM NTLM_WB PSL SPNEGO SSL TLS-SRP UnixSockets


➜  ~ wget --version
GNU Wget 1.20.3 built on linux-gnu.


<br>

<h3>REST APIs end points</h3>


</code></pre>
