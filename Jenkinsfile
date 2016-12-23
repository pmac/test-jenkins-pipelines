switch ( env.BRANCH_NAME ) {
    case "master":
        echo "Building master"
        // build '../other-repo/master'
    case { it ==~ /^demo__\w/ }:
        echo "Building a demo: ${it}"
    default:
        echo "Doing nothing for ${it}"
}
