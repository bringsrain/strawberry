## vim

- <https://github.com/chriskempson/base16-vim/blob/master/colors/base16-default-light.vim> `c1c3e6c`
- <https://github.com/chriskempson/base16-vim/blob/master/colors/base16-default-dark.vim> `c1c3e6c`

```
3,10d | 4d | 5d | 36d | 42,49d |
4s#.*/#execute "silent !/bin/sh $HOME/.nightshell/# |
4s/\.sh// |
%s/base16-default/princess/ |

%s/181818/1f171b/ |
%s/282828/30242a/ |
%s/383838/523d47/ |
%s/585858/705462/ |
%s/b8b8b8/997386/ |
%s/d8d8d8/bf8fa7/ |
%s/e8e8e8/e8ccda/ |
%s/f8f8f8/ffebf5/ |

%s/ab4642/bf5050/ |
%s/dc9656/bf7730/ |
%s/f7ca88/ab8b2b/ |
%s/a1b56c/569456/ |
%s/86c1b9/569494/ |
%s/7cafc2/608fbf/ |
%s/ba8baf/8f72ab/ |
%s/a16946/bf6f98/ |

%s/Character",    s:gui08, "", s:cterm08/Character",    s:gui0F, "", s:cterm0F/ |
%s/Cursor",        s:gui00, s:gui05, s:cterm00, s:cterm05/Cursor",        s:gui00, s:gui0F, s:cterm00, s:cterm0F/ |
%s/CursorLineNr",  s:gui04, s:gui01, s:cterm04, s:cterm01/CursorLineNr",  s:gui00, s:gui03, s:cterm00, s:cterm03/ |
%s/Identifier",   s:gui08, "", s:cterm08, "", "none/Identifier",   s:gui0F, "", s:cterm0F, "", "bold/ |
%s/LineNr",        s:gui03, s:gui01, s:cterm03/LineNr",        s:gui04, s:gui01, s:cterm04/ |
%s/MatchParen",    "", s:gui03, "", s:cterm03/MatchParen",    s:gui00, s:gui03, s:cterm00, s:cterm03/ |
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

%s#18/18/18#1f/17/1b# |
%s#28/28/28#30/24/2a# |
%s#38/38/38#52/3d/47# |
%s#58/58/58#70/54/62# |
%s#b8/b8/b8#99/73/86# |
%s#d8/d8/d8#bf/8f/a7# |
%s#e8/e8/e8#e8/cc/da# |
%s#f8/f8/f8#ff/eb/f5# |
%s#ab/46/42#bf/50/50# |
%s#dc/96/56#bf/77/30# |
%s#f7/ca/88#ab/8b/2b# |
%s#a1/b5/6c#56/94/56# |
%s#86/c1/b9#56/94/94# |
%s#7c/af/c2#60/8f/bf# |
%s#ba/8b/af#8f/72/ab# |
%s#a1/69/46#bf/6f/98# |

%s/181818/1f171b/ge |
%s/383838/523d47/g |
%s/d8d8d8/bf8fa7/g |
%s/f8f8f8/ffebf5/ge |

call append(123,["",
"echo -ne '\\e]12;#bf6f98\\a'"])
```
