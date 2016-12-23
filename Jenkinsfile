def branch = env.BRANCH_NAME;

if ( branch == 'master') {
    echo "Building master"
    // build '../other-repo/master'
}
else if ( branch ==~ /^demo__\w/ ) {
    echo "Building a demo: ${branch}"
}
else {
    echo "Doing nothing for ${branch}"
}
