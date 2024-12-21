This is a kubernetes cluster Powered by TrueCharts ClusterTool


Manual flux recon
```bash
flux reconcile source git cluster -n flux-system
```
Check for issues:
```bash
flux get all -A --status-selector ready=false
```