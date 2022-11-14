# OpenAPI manifests for our APIs

This repo stores manifests, created with our customized [swagger editor](https://swagger-editor.rollun.net/)


## Swagger editor

Production ready files saved to master, drafts - to develop

### Features:

1. Read/delete files from this git repo to Your swagger editor

Using button **Open manifest**
![](/docs/github-interop.png)

Select any manifest from list to edit (button **Use**), or delete (button **Delete**) <br/>
If You did some changes to this git ropository for other swagger editor or using git, press **Force refetch manifests**, to fetch current manifests from scratch.
![](/docs/read-delete-manifests.png)


2. Flush Your changes from swagger editor to this repo

> Для того щоб зберегти маніфест в цей репозиторій у вас повинно бути встановлено гітхаб токен з правами на запис в цей репозиторій.
> Створити гітхаб токен можно за посиланням https://github.com/settings/tokens . 
> Гітхаб токен у вас запитають при першому відкритті едітора, надалі його можно змінити натиснувши reset github token

Using button **Save current manifest**
![](/docs/github-interop.png)

You will be prompted for save mode (Production or draft)
Press **Save**, to flush Your current file to git  <br/>
If no such file on git, it will be created, <br/>
If there is one, it will be updated.

![](/docs/save-manifest.png)


