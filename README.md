# SideQuestz — support site

The public pages behind the app's **Support URL** and **Privacy Policy URL**
on the App Store.

**Generated, not hand-written.** The source is the SideQuestz app itself: the
contact address comes out of `Support.swift`, the terms out of `Terms.swift`
word for word, the retention numbers out of `ClipStore` and `Account`, and the
colours out of the app's audited palettes. Editing a page here would only put
the site out of step with the app.

To change anything, change it in the app and rerun:

    python3 tools/site/build_site.py --mirror /path/to/sidequestz-site

then commit and push whatever it rewrote.
