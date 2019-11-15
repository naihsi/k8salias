#k8salias

# set up 
download to your .bashrc to use the aliases

```
curl https://raw.githubusercontent.com/naihsi/k8salias/master/k8salias -o ~/.k8salias
```

and add the script into your .bashrc:

```
if [ -f ~/.k8salias ]; then
          . ~/.k8salias
fi
  ```

finally reload it

```
source ~/.bashrc
```
