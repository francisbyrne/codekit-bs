# codekit-bs
Error for codekit v2.2 with bootstrap v2.3.1

## To reproduce

1. Clone repo
2. Open Codekit
3. Open main.less in text editor
4. Edit something and save
5. Codekit throws the following error:

```
Main.less:
NameError: #grid > .core > .span is undefined in [Some Path]/codekit-bs/bootstrap/less/navbar.less on line 199, column 3:
 .navbar-fixed-bottom .container {
   #grid > .core > .span(@gridColumns);
   }
```
