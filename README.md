# deta-create-micro-action
Simple GitHub Action to create new micro

```yaml
- name: Create micro on deta
  uses: jhihyulin/deta-create-micro-action@v1.0.0
  with:
    deta-access-token: '' #Deta access token https://docs.deta.sh/docs/cli/auth
    deta-name: '' #Deta Micro name https://docs.deta.sh/docs/cli/commands/#deta-clone
    deta-project: '' #Optional: Deta project name https://docs.deta.sh/docs/cli/commands/#deta-clone
    deta-project-dir: '' #Optional: directory to be deployed on Deta. Default is the root "."
    deta-runtime-version: '' #python3.7 python3.9 
