# libreelec-git

Update your .profile with the following alias
<code>
function git () {
    (docker run -ti --rm -v ${HOME}:/root -v $(pwd):/git synopsis8/libreelec-git "$@")
}
</code>
