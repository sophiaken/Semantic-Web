# myfamily_facts.ttl depends on myfamily.ttl and myrules.n3

myfamily_facts.ttl : myfamily.ttl myrules.n3
	cwm -n3 myfamily.ttl -think=hw3_rules.n3 -think=myrules.n3 > myfamily_facts.ttl

clean :
	rm myfamily_facts.ttl

