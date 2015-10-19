Beelzebub Plugin for Sublime Text
========================

This plugin is a mixture of [C++ Starting Kit](https://github.com/kodLite/cppStartingKit) and the [Oasis Theme](https://github.com/kodLite/Oasis-Theme).  

It fixes **several** issues with the former (some also present in the default C++ language definition that's shipped with Sublime), adds some of the **promised** features to the latter, and alters the color scheme significantly.  

![screenie](https://u.vercas.com/20151019031445-1445220885-126-2fvK.png)

Also, I have added more keywords, operators and C++11 types to the language definition.
Besides these, there are some of the most common Beelzebub classes and variables which will now stand out a bit more.  

## Installation

You should put the contents of this repository in `Data/Packages/Beelzebub`. I hope.
That's where I keep it.  

Should you decide to use this, you may have a hard time telling Sublime to use this instead of the default C++ highlighting. If this is the case, I recommend disabling the default `C++` package through your user preferences:

    "ignored_packages":
    [
        "C++"
    ]

You will lose the snippets. But they're utterly useless anyway.
I shall add Beelzebub-specific snippets as required.
