## Shortcuts 

1, Clone : `git clone https://github.com/bybai/xCAT_features.git`

2, Execute playbooks under `xCAT_features/xcat-automation`: `ansible-playbook -i hosts fast_cluster.yaml`

**Notes**: default running on `localhost`, if runnig on different nodes, adding these nodes names in the hosts file. If need costomize variables, modify xcat-automation/fast_cluster.yaml. If need customize xcat-inventory data, modify xcat-automation/templates/

### Useful commands

* `ansible-playbook -i hosts fast_cluster.yaml --list-hosts`
* To find out the variables and inventory available on the hosts: 

   `ansible -m setup -i hosts <hostname>`

```javascript
<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-129336035-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-129336035-1');
</script>

``` 
