# mycat-starter

Unknown column '_slot' in 'field list' 
使用的分片规则为crc32slot时，默认会在一条记录里加上"_slot"这个column，所以在物理表中增加"_slot"这个column即可解决此问题
