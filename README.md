# patch-file
# This is a comment.
# Each line is a file pattern followed by one r more owners.
# These owners will be the default owners for everything in 
# The repo.Unless a later match takes precedence,
# @global-owner1 and @global-owner2 wil be requested for
# review when someone opens a pull request.
*      @global-owner1 @global-owner2
