Tailscale Start Action
======================

> [!NOTE]
> Modified to start Tailscale when preinstalled in container/image,
> and remove warnings for authkeys


This GitHub Action connects to your [Tailscale network](https://tailscale.com)
by adding a step to your workflow.

```yaml
  - name: Tailscale
    uses: gbraad-actions/start-tailscale@v1
    with:
      authkey: tskey-auth-...
```
