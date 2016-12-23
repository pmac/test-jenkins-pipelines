switch ( env.BRANCH_NAME ) {
    case "master":
        echo "Building master"
        // build '../other-repo/master'
    case { it ==~ /^demo__\w/ }:
        echo "Building a demo: ${env.BRANCH_NAME}"
    default:
        echo "Doing nothing for ${env.BRANCH_NAME}"
}
