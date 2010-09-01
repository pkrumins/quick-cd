Quick cd keeps tracks of directoreis you work the most often and allows you
to cd to them in the blink of an eye.

It was written by Peteris Krumins (@pkrumins or peter@catonmat.net).
His blog is at http://www.catonmat.net  --  good coders code, great reuse.

------------------------------------------------------------------------------

First `git clone http://github.com/pkrumins/quick-cd`, then make sure to alias
your cd to qcd,

    alias cd=qcd

This will record all the directories you ever work in.

After that, bind a keystroke to bring up the list quickly,

    bind "\C-[d": "qcd\n"

Now each time you hit Alt-d (or Esc-d), quick cd will pop up a list of most
frequently used directories.

Now if you can use arrow keys to navigate the list, or type a pattern to find
a dir. Hit enter and you'll be transferred to that directory.

That should make you super fast in the shell!

------------------------------------------------------------------------------

Have fun being quicker in the shell!


Sincerely,
Peteris Krumins
http://www.catonmat.net

