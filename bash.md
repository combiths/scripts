## Remove text after 2nd to last hyphen
echo hello-world-test | sed -E 's/-[^-]+-[^-]+$//'


