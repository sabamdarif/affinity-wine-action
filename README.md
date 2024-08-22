
![Logo](https://codeberg.org/wanesty/affinity-wine-docs/raw/branch/guide-wine9.13-part3/publisher-wine.avif)
> Orginal image is from : https://codeberg.org/wanesty/affinity-wine-docs


# Build ElementalWarrior Wine In GitHub Action

Build ElementalWarrior's Wine using github action to run Affinity apps in linux



## Acknowledgements

 - [affinity-wine-docs](https://codeberg.org/wanesty/affinity-wine-docs)
 - [ElementalWarrior Wine](https://gitlab.winehq.org/ElementalWarrior/wine.git)


## Documentation

[Orginal Step By Step Documentation](https://codeberg.org/wanesty/affinity-wine-docs)
## How to setup the workflow

**Don't rename the fork , because i use [absolute path](https://www.redhat.com/sysadmin/linux-path-absolute-relative) in the yml file `/home/runner/work/affinity-wine/` insted of `$HOME`**

- Go to your github account [setting](https://github.com/settings/profile)
- Go to [Developer Settings](https://github.com/settings/tokens)
- There under `Personal access tokens` , go to [token clasic](https://github.com/settings/tokens)
- Click on `Generate New Token` and `Generate new token (clasic)`
- Generate the token
- Copy it
- Open the fork repo
- Under `Security` click on `Secrets and variables`
- Click on `Actions`
- Create `new repository secret`
- Name it **`TOKEN_TO_UPLOAD`**
- In value section put Generated token and save it
- Now run the workflow