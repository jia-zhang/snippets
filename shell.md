#send mail for 1000 times
for i in {1..1000}; do swaks -S -s 172.31.7.171 -f test@aaa.com -t test1@ectest.hes20.net -d 'sample/AFI/1 zip contains 4 files and marco is 4th.eml'; done

