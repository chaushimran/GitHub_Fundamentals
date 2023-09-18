
[Generating a new SSH key and adding it to the ssh-agent](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

```
ls -al ~/.ssh
```
```
 ssh-keygen -t rsa -b 4096 -C "cloud.chaush@gmail.com"
```
```
eval "$(ssh-agent -s)"
```
```
ssh-add ~/.ssh/id_rsa
```
```
cd ~/.ssh
```
```
cat id_rsa.pub
```


[Add SSH-Key](https://github.com/settings/ssh/new)
