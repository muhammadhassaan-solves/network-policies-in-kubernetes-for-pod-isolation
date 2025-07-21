<h1>Network Policies in Kubernetes for Pod Isolation</h1>


<h2>Description</h2>
This project demonstrates how to secure pod-to-pod communication in Kubernetes using NetworkPolicies. It focuses on isolating sensitive workloads by blocking all ingress traffic by default and allowing only specific traffic based on pod labels and namespace.
<br />


<h2>Tools and Technologies</h2>

- Kubernetes
- NetworkPolicy
- kubectl
- YAML
- BusyBox
- netcat 

<h2>Project Walk-through</h2>

<p align="center">
Set up the environment <br />
<img src="https://i.postimg.cc/zfFLbzpj/1.jpg"/>
<br />
<br />
Apply a deny-all policy <br/>
<img src="https://i.postimg.cc/Pr5002Br/3.jpg" />
<br />
<br />
Allow specific access and Test communication  <br/>
<img src="https://i.postimg.cc/nVP1c2XL/4.jpg"/>
<br />
<br />
Validate namespace isolation <br/>
<img src="https://i.postimg.cc/fRs4BmxM/5.jpg" />
<br />
<br />


</p>

