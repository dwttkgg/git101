# git101

#Notes on git
Git clone == copy repo to your computer.
Git status == show you the status of your files.
Git add --all == adding files to be saved .
Git commit == save changes to files in your repository.
Git push == send files to the remote server at github.com.


# switching branches
Git branch == make a new copy/branch
Git checkout branch_name == moves you into copy branch_name

# git push   OpenSSL SSL_read: Connection was reset, errno 10054
# The SSL certificate of the server has not been signed by a third party
# Solutions
git config --global http.sslVerify "false"
git config --global https.sslVerify "false"
cat ~/.gitconfig
