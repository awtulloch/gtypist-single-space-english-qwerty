# gtypist single space English QWERTY

This is a fork of [gtypist-single-space](https://github.com/inaimathi/gtypist-single-space) which is a copy of the default [GNU Typist](http://www.gnu.org/software/gtypist/) lessons with all the "two spaces at the end of each sentence" and "use l instead of 1" garbage thrown out.

- Non-English language, Dvorak and Colemak courses have been removed.
- The kten.typ (Ktouch English) and p.typ (programming) courses have been integrated into gtypist.typ.

### Usage

Just copy these files to your gtypist directory (if you're using Debian and installed the `gtypist` package through `apt-get`, your `.typ`s should be in `/usr/share/gtypist/`), overwriting the old ones. Trust me, it's better this way.

### Contents Notes

The files

- demo.typ
- gtypist.typ
- m.typ
- n.typ
- q.typ
- r.typ
- s.typ
- t.typ
- u.typ
- v.typ

have all been edited for spacing. Double spaces are removed everywhere, paragraph indentation has been removed, and documentation regarding the requirement for the above has been removed.

The files **gtypist.typ** and **t.typ** contained a set of three lessons wherein the typist is expected to substitute `l` (lowercase L) for `1` (the numeral One). These have been removed entirely.

The **gtypist.typ** and **r.typ** files have a section with a user-formatted index of items with (manual) connecting dot lines. The columns are also vertically aligned (also manual). This doesn't seem like something humans should even learn anymore, but it doesn't work without extraneous spaces, so they've been left in.
