# xss

Setup own xsshunter for Blind XSS: https://www.intigriti.com/researchers/blog/hacking-tools/hacker-tools-xsshunter

My own xss hunter : xsshunter.juhi.store/admin


==========
Automate XSS (mac)

echo http://testphp.vulnweb.com/ | gau | gf xss | uro | Gxss| kxss| tee xss_out.txt

cat xss_out.txt | grep -oE '^URL: [^ ]+' xss_out.txt | sed -E 's/^URL: //; s/=[^&]*/=/g' | sort -u > final.txt

cd loxs
python3 loxs.py
Select Option 4 - XSS ==> filename ===>payloads/xss.txt ====> enter

Reference video: https://www.youtube.com/watch?v=cRL9REGSKkM
===========
