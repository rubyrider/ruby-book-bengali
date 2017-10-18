# ইন্টারেক্টিভ রুবি- Interactive Ruby

আমরা ইতিমধ্যেই Interactive Ruby বা IRB এর সম্পর্কে ধারনা পেয়েছি। এই বার IRB এর বিস্তারি আমরা জানার চেষ্টা করবো। আমরা জেনেছি 

IRB একটু ইন্টারেক্টিভ রুবি টুল। আমরা রুবির কোন কোড লিখলেই সেটা পরের লাইনে আউটপুট প্রিন্ট করে। কিন্তু এই IRB দিয়ে আরো অনেক কাজ করা যায়। আরো অনেক ভাবে আমরা রুবি কোড রান করাতে পারি। যেমন যেকোন রুবি ফাইলকে IRB এর মাধ্যমেও রান করাতে পারি। সামনের চ্যাপ্টারে আগানোর আগে আমাদের IRB নিয়ে ভালো থাকা ধারনা করা প্রয়োজন। এতে করে আমরা পরবর্তি এবং নতুন ফিচার গুলো অনেক সহজে নিজেরাই প্রাকটিস এবং যাচাই করতে পারবো। যা খুব শীঘ্রই রুবিকে বোঝার বেপারে আমাদের হেল্প হবে। 



আমরা ইতিমধ্যে জেনেছি যে IRB এর পুরো অর্থ- Interactive Ruby।  এখন আমরা  IRB এর কমান্ড লাইন অপশন গুলো দেখবো। এই অপশনগুলো দেখতে হলে আপনাকী নিচের কমান্ডটি চালাতে হবে। 

`irfanahmed@Irfans-MacBook-Pro code-examples (master)$ irb --help`

`Usage:  irb.rb [options] [programfile] [arguments]`

`  -f		    Suppress read of ~/.irbrc`

`  -m		    Bc mode (load mathn, fraction or matrix are available)`

``  -d                Set $DEBUG to true (same as `ruby -d')``

``  -r load-module    Same as `ruby -r'``

`  -I path           Specify $LOAD_PATH directory`

``  -U                Same as `ruby -U```

``  -E enc            Same as `ruby -E```

``  -w                Same as `ruby -w```

``  -W[level=2]       Same as `ruby -W```

`  --context-mode n  Set n[0-3] to method to create Binding Object,`

`                    when new workspace was created`

`  --echo            Show result(default)`

`  --noecho          Don't show result`

``  --inspect	    Use `inspect' for output (default except for bc mode)``

`  --noinspect	    Don't use inspect for output`

`  --readline        Use Readline extension module`

`  --noreadline	    Don't use Readline extension module`

`  --prompt prompt-mode/--prompt-mode prompt-mode`

`		    Switch prompt mode. Pre-defined prompt modes are`

``		    `default', `simple', `xmp' and `inf-ruby'``

`  --inf-ruby-mode   Use prompt appropriate for inf-ruby-mode on emacs.`

`		    Suppresses --readline.`

`  --sample-book-mode/--simple-prompt`

`                    Simple prompt mode`

`  --noprompt        No prompt mode`

`  --single-irb      Share self with sub-irb.`

`  --tracer          Display trace for each execution of commands.`

`  --back-trace-limit n`

`		    Display backtrace top n and tail n. The default`

`		    value is 16.`

`  --irb_debug n	    Set internal debug level to n (not for popular use)`

`  --verbose         Show details`

`  --noverbose       Don't show details`

`  -v, --version	    Print the version of irb`

`  -h, --help        Print help`

`  --                Separate options of irb from the list of command-line args`

