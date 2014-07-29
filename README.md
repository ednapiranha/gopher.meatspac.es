# Meatspace Gopherspace

This is the meatspace gopher repository. 

gopher://gopher.meatspac.es/

## If you want to add yourself ...

Note that the gophermap file requires hard tabs (not spaces) for linking the directories.

More about the [gophermap](http://en.wikipedia.org/wiki/Gophermap) format.

For a quick reference, this is what you can set up in your gophermap file for various links:

    0 = text
    1 = gopher menu
    5 = zip file
    7 = search server
    9 = generic binary
    I = generic image
    g = gif image
    s = sound or audio file
    h = HTML

For linking to an external URL, you would do something like:

`hA link to Google<TAB>/URL:http://google.com/`

where `<TAB>` is the actual hard tab.

## Structuring your content

If you plan to link to a lot of external or internal content, you should just create a subdirectory under your username with a gophermap file. For example, if you are writing blog posts, you might create a subdirectory named 20140101 and have a gophermap within that directory that is your post.

    - <your username dir>
      - gophermap (with gopher menu links to the subdirectories)
      - <20140101 dir>
        - gophermap
        - any internal files you want to reference for this post
