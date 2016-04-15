lis[i].innerHTML = lis[i].innerHTML.replace("<span id=\"result\">"+latest+"</span>", latest);
这句话加在第二个for里就会有错：插入as和a，然后先分别搜索a和s，
然后搜索as，第一遍点查询的时候as不变色，第二次点击的时候才变色。
但是在for之外先全部清除样式就是没问题的。
有什么区别吗？