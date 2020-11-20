
#### Incident Issue

If this report is linked to an ~incident issue link it here: #INCIDENT ISSUE NUMBER

## General Information

What service is exhibiting issues:

- [ ] `https`
- [ ] `ssh`

Brief description of the behavior:

#### Minimum Tracing

Please run the following commands and paste the output below. This will include
the Cloudflare Point-of-presence code which will indicate your general geographic
location:

<p>
<details>
<summary>`curl -v http://gitlab.com/cdn-cgi/trace`</summary>

<pre><code>PASTE OUTPUT HERE</code></pre>

</details>
</p>

<p>
<details>
<summary>`curl https://gitlab.com/cdn-cgi/trace`</summary>

<pre><code>PASTE OUTPUT HERE</code></pre>

</details>
</p>

<p>
<details>
<summary>`curl -svo /dev/null https://gitlab.com`</summary>

<pre><code>PASTE OUTPUT HERE</code></pre>

</details>
</p>

#### Optional Additional Information

The following information may include your own IP address or private group
and project paths. Consider making this issue `Confidential` before including it.


GitLab username if other than reporter:


If the problem is with specific URI, please paste them below:

- https://gitlab.com/mygroup/myproject
- ...


<p>
<details>
<summary>`traceroute gitlab.com`</summary>

<pre><code>PASTE OUTPUT HERE</code></pre>

</details>
</p>

#### For the Gitlab Team

- [Cloudflare Grafana Dashboard](https://dashboards.gitlab.net/d/sPqgMv9Zk/cloudflare-traffic-overview?orgId=1&refresh=30s)
- [Cloudflare Dashboard](https://dash.cloudflare.com)
  - [GitLab.com Firewall Overview](https://dash.cloudflare.com/852e9d53d0f8adbd9205389356f2303d/gitlab.com/firewall)

##### `rails` and other application logs

<!-- Link to elastic short urls here -->

##### Cloudflare logs and `dash.cloudflare.com` results

<!-- -->


#### Labels and things


/label ~team::Core-infra ~security ~service::Cloudflare


#### Additional reports

As additional reports are received, please record them as comments below. This
template can be used:

```
<p>
<details>
<summary>`curl -v http://gitlab.com/cdn-cgi/trace`</summary>

<pre><code>PASTE OUTPUT HERE</code></pre>

</details>
</p>

<p>
<details>
<summary>`curl -v http://gitlab.com/cdn-cgi/trace`</summary>

<pre><code>PASTE OUTPUT HERE</code></pre>

</details>
</p>

<p>
<details>
<summary>`curl -svo /dev/null https://gitlab.com`</summary>

<pre><code>PASTE OUTPUT HERE</code></pre>

</details>
</p>

```
