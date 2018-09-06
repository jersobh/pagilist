# Pagilist

Simple module to paginate lists using page or limit/offset. Source code available at
[Github](https://github.com/jersobh/pagilist).

### Usage
<pre>
page = 0 #first page
limit = 3 #three items per page
page_sample = paginate(list, page, limit)

##OR##

offset = 3 #start from the third element on list
page_offset = paginate_offset(list, page, 5) #get from the third element to fifth element

print(page_sample) #outputs [1, 2, 3]
print(page_offset) #outputs [1, 2, 3, 4, 5]
</pre>