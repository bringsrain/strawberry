## vim

- <https://github.com/chriskempson/base16-vim/blob/master/colors/base16-default-light.vim> `c1c3e6c`
- <https://github.com/chriskempson/base16-vim/blob/master/colors/base16-default-dark.vim> `c1c3e6c`

```
3,10d | 4d | 5d | 36d | 42,49d |
4s#.*/#execute "silent !/bin/sh $HOME/.nightshell/# |
4s/\.sh// |
%s/base16-default/princess/ |

%s/181818/1f191c/ |
%s/282828/30282c/ |
%s/383838/52444b/ |
%s/585858/705d67/ |
%s/b8b8b8/997f8c/ |
%s/d8d8d8/bf9faf/ |
%s/e8e8e8/e8c1d4/ |
%s/f8f8f8/ffebf5/ |

%s/ab4642/bf6060/ |
%s/dc9656/bf7f3f/ |
%s/f7ca88/ab8e38/ |
%s/a1b56c/639463/ |
%s/86c1b9/639494/ |
%s/7cafc2/6387ab/ |
%s/ba8baf/816f94/ |
%s/a16946/ab8096/ |

%s/Character",    s:gui08, "", s:cterm08/Character",    s:gui0F, "", s:cterm0F/ |
%s/Cursor",        s:gui00, s:gui05, s:cterm00, s:cterm05/Cursor",        s:gui00, s:gui0F, s:cterm00, s:cterm0F/ |
%s/Identifier",   s:gui08, "", s:cterm08, "", "none/Identifier",   s:gui0F, "", s:cterm0F, "", "bold/ |
%s/LineNr",        s:gui03, s:gui01, s:cterm03/LineNr",        s:gui04, s:gui01, s:cterm04/ |
%s/Search",        s:gui03, s:gui0A, s:cterm03, s:cterm0A/Search",        s:gui00, s:gui09, s:cterm00, s:cterm09/ |
%s/statusline",    s:gui04, s:gui02, s:cterm04, s:cterm02/statusline",    s:gui00, s:gui0F, s:cterm00, s:cterm0F/ |
%s/StatusLineNC",  s:gui03, s:gui01, s:cterm03, s:cterm01/StatusLineNC",  s:gui05, s:gui01, s:cterm05, s:cterm01/ |
%s/Visual",        "", s:gui02, "", s:cterm02/Visual",        s:gui06, s:gui02, s:cterm06, s:cterm02/ |
%s/VisualNOS",     s:gui08, "", s:cterm08, "", ""/VisualNOS",     "", s:gui01, "", s:cterm01, "none"/ |
%s/WildMenu",      s:gui08, s:gui0A, s:cterm08, ""/WildMenu",      s:gui00, s:gui06, s:cterm00, s:cterm06/ |

normal =gg
```

## nightshell

- <https://raw.githubusercontent.com/chriskempson/base16-shell/master/scripts/base16-default-light.sh> `376294b`
- <https://raw.githubusercontent.com/chriskempson/base16-shell/master/scripts/base16-default-dark.sh> `376294b`

```
2,4d |

%s#18/18/18#1f/19/1c# |
%s#28/28/28#30/28/2c# |
%s#38/38/38#52/44/4b# |
%s#58/58/58#70/5d/67# |
%s#b8/b8/b8#99/7f/8c# |
%s#d8/d8/d8#bf/9f/af# |
%s#e8/e8/e8#e8/c1/d4# |
%s#f8/f8/f8#ff/eb/f5# |
%s#ab/46/42#bf/60/60# |
%s#dc/96/56#bf/7f/3f# |
%s#f7/ca/88#ab/8e/38# |
%s#a1/b5/6c#63/94/63# |
%s#86/c1/b9#63/94/94# |
%s#7c/af/c2#63/87/ab# |
%s#ba/8b/af#81/6f/94# |
%s#a1/69/46#ab/80/96# |

%s/181818/1f191c/ge |
%s/383838/52444b/g |
%s/d8d8d8/bf9faf/g |
%s/f8f8f8/ffebf5/ge |

call append(123,["",
"echo -ne '\\e]12;#ab8096\\a'"])
```
