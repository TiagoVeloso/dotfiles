# Usage tap 'homebrew/bundle'
# Then 'brew bundle'

tap 'homebrew/bundle'
tap 'homebrew/versions'

# Install GNU core utilities (those that come with OS X are outdated).
# Don’t forget to add `$(brew --prefix coreutils)/libexec/gnubin` to `$PATH`.
brew 'coreutils'
#sudo ln -s /usr/local/bin/gsha256sum /usr/local/bin/sha256sum

# Install some other useful utilities like `sponge`.
brew 'moreutils'
# Install GNU `find`, `locate`, `updatedb`, and `xargs`, `g`-prefixed.
brew 'findutils'
# Install GNU `sed`, overwriting the built-in `sed`.
brew 'gnu-sed', args: ['with-default-names']

# Install Bash 4.
# Note: don’t forget to add `/usr/local/bin/bash` to `/etc/shells` before
# running `chsh`.
brew 'bash'
brew 'bash-completion2'

# Install `wget` without IRI support.
brew 'wget' #, args: ['with-iri']

# Install more recent versions of some OS X tools.
brew 'vim', args: ['override-system-vi']
brew 'homebrew/dupes/grep'
brew 'homebrew/dupes/openssh'
brew 'homebrew/dupes/screen'
# brew 'homebrew/php/php55', args: ['with-gmp']

# Install font tools.
# tap 'bramstein/webfonttools'
# brew 'sfnt2woff'
# brew 'sfnt2woff-zopfli'
# brew 'woff2'

# Install some CTF tools; see https://github.com/ctfs/write-ups.
# brew 'aircrack-ng'
# brew 'bfg'
# brew 'binutils'
# brew 'binwalk'
# brew 'cifer'
# brew 'dex2jar'
# brew 'dns2tcp'
# brew 'fcrackzip'
# brew 'foremost'
# brew 'hashpump'
# brew 'hydra'
# brew 'john'
# brew 'knock'
# brew 'netpbm'
# brew 'nmap'
# brew 'pngcheck'
# brew 'socat'
# brew 'sqlmap'
# brew 'tcpflow'
# brew 'tcpreplay'
# brew 'tcptrace'
# brew 'ucspi-tcp' # `tcpserver` etc.
# brew 'xpdf'
# brew 'xz'

# Install Android SDK
brew 'android-sdk'
brew 'xctool'
brew 'rbenv'

brew 'git'
brew 'git-flow'
brew 'imagemagick', args: ['with-webp']
brew 'p7zip'
brew 'pigz'
brew 'rename'
brew 'speedtest_cli'
brew 'ssh-copy-id'
brew 'tree'
brew 'webkit2png'
brew 'zopfli'

# brew 'ack'
# brew 'dark-mode'
# brew 'exiv2'
# brew 'lua'
# brew 'lynx'
# brew 'pv'
# brew 'rhino'
