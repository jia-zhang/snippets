#Match across lines:
sed -ie ":begin; /<$key>/,/<\/$key>/ { /<\/$key>/! { $! { N; b begin }; }; s/<$key>.*<\/$key>/<$key>$value<\/$key>/; };" $template
