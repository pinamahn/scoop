# nitter

`find ./ -type f \( -iname \*.iml -o -iname \*gradle  -o -iname \*.java -o -iname \*flags -o -iname \*mk -o -iname \*h -o -iname \*cpp -o -iname \*rs  -o -iname \*xml  \)  -printf '%P\n'  -exec perl -pi -e 's/old/new/g' '{}' \+`
