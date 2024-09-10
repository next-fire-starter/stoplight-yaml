# stoplight-yaml


git submodule add -b main https://github.com/next-fire-starter/webdocs aaaa


git -C ref/aaaa config core.sparsecheckout true


git -C ref/aaaa config -l

vi .git/modules/ref/aaaa/info/sparse-checkout

/design-document/


git -C ref/aaaa read-tree -mu HEAD

git submodule update --init