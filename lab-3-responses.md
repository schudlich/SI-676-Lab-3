[Jekyll Test Site](https://schudlich.github.io/test-jekyll-20250912/)
- Use the dig command to query umich.edu. What is the response and how would you explain it?
> The response to this command provides relevant DNS information for the provided domain. The umich.edu response includes two different IP addresses: 162.159.140.37 (IPv6) and 172.66.0.37 (IPv4)
- Use the command for the above response, and pipe the output to a file named umich-dns-record.txt. Provide the text file.
- Use the dig command to query umich.edu. What is the command to return only the “answer” section of the response?
> dig +noall +answer umich.edu
