While we wait for the [mimemagic fiasco](https://www.theregister.com/2021/03/25/ruby_rails_code/) to clear up, you can use this repo to run the version of `mimemagic` you used to run. **This is GPL code. Don't use it if that's a problem for you.**

To use this:

```ruby
gem "mimemagic", git: "https://github.com/TandaHQ/mimemagic-but-gpl.git", ref: "40dd02bb6b442535f97c35326c0383bc67146ac4"
```

You can use any ref you like, [`40dd02bb6b442535f97c35326c0383bc67146ac4`](https://github.com/mimemagicrb/mimemagic/tree/40dd02bb6b442535f97c35326c0383bc67146ac4) is the last ref before the licensing changes started. You can [verify this](https://github.com/mimemagicrb/mimemagic/commits/master?after=ffcff44bc1c5070fff94f67e6ac5b81135e5d853+34&branch=master) in the repo's history.

The only reason this fork exists is in case the https://github.com/mimemagicrb/mimemagic gets yanked or its history rewritten. You may want to consider your own fork.
