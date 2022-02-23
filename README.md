- Error message in Neovim:
```shell
Output directory does not exist at '/home/schmidh/Gitrepos/qqqq/.spago/console/v5.0.0/output'. Ensure project is built, or check configuration of output directory and build command..                  
                                                                                                                                                                                                        
Ensure project is built with the same purs version as the IDE server is using                                                                                                                           
                                                                                                                                                                                                        
Request Actions:                                                                                                                                                                                        
1. Build project                                                                                                                                                                                        
Type number and <Enter> or click with the mouse (q or empty cancels):    
```

- Spago is locally installed. Neovim finds it (e.g :r !spago sources, works fine):
```shell
$ which spago
$ node_modules/.bin/spago
```
