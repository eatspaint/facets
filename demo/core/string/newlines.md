## String#newlines

Since Ruby 1.9 defined #lines to keep the newline character,
we have defined #newlines to leave them out.

    require 'facets/string/newlines'

    "a\nb\nc".newlines.to_a.assert == ["a","b","c"]

