def branch = env.BRANCH_NAME;

if ( branch == 'master') {
    echo "Building master"
    build 'testing_running_other_jobs'
}
else if ( branch ==~ /^demo__[a-z_-]+$/ ) {
    echo "Building a demo: ${branch}"
    echo "TODO: make this work"
}
else {
    echo "Doing nothing for ${branch}"
}
