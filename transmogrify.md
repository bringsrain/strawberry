## vim

- <https://github.com/chriskempson/base16-vim/blob/master/colors/base16-default-light.vim> `c1c3e6c`
- <https://github.com/chriskempson/base16-vim/blob/master/colors/base16-default-dark.vim> `c1c3e6c`

```
3,10d | 4d | 5d | 36d | 42,49d |
4s#.*/#execute "silent !/bin/sh $HOME/.nightshell/# |
4s/\.sh// |
%s/base16-default/princess/ |

%s/181818/1f1218/ |
%s/282828/301c26/ |
%s/383838/523744/ |
%s/585858/704b5e/ |
%s/b8b8b8/996780/ |
%s/d8d8d8/bf80a0/ |
%s/e8e8e8/e8aecb/ |
%s/f8f8f8/ffd4e9/ |

%s/ab4642/d44646/ |
%s/dc9656/d46a00/ |
%s/f7ca88/bf8f00/ |
%s/a1b56c/3e943e/ |
%s/86c1b9/199494/ |
%s/7cafc2/3f7fbf/ |
%s/ba8baf/8f60bf/ |
%s/a16946/d47ba7/ |

%s/Character",    s:gui08, "", s:cterm08/Character",    s:gui0F, "", s:cterm0F/ |
%s/Cursor",        s:gui00, s:gui05, s:cterm00, s:cterm05/Cursor",        s:gui00, s:gui0F, s:cterm00, s:cterm0F/ |
%s/Identifier",   s:gui08, "", s:cterm08, "", "none/Identifier",   s:gui0F, "", s:cterm0F, "", "bold/ |
%s/LineNr",        s:gui03, s:gui01, s:cterm03/LineNr",        s:gui04, s:gui01, s:cterm04/ |
%s/Search",        s:gui03, s:gui0A, s:cterm03, s:cterm0A/Search",        s:gui00, s:gui0A, s:cterm00, s:cterm0A/ |
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

%s#18/18/18#1f/12/18# |
%s#28/28/28#30/1c/26# |
%s#38/38/38#52/37/44# |
%s#58/58/58#70/4b/5e# |
%s#b8/b8/b8#99/67/80# |
%s#d8/d8/d8#bf/80/a0# |
%s#e8/e8/e8#e8/ae/cb# |
%s#f8/f8/f8#ff/d4/e9# |
%s#ab/46/42#d4/46/46# |
%s#dc/96/56#d4/6a/00# |
%s#f7/ca/88#bf/8f/00# |
%s#a1/b5/6c#3e/94/3e# |
%s#86/c1/b9#19/94/94# |
%s#7c/af/c2#3f/7f/bf# |
%s#ba/8b/af#8f/60/bf# |
%s#a1/69/46#d4/7b/a7# |

%s/181818/1f1218/ge |
%s/383838/523744/g |
%s/d8d8d8/bf80a0/g |
%s/f8f8f8/ffd4e9/ge |

call append(123,["",
"echo -ne '\\e]12;#d47ba7\\a'"])
```
