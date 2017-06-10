# assignment17.2

create 'clicks','hits'
alter 'clicks', NAME => 'hits',VERSIONS => 5
put 'clicks','rw01','hits','name:ramesh'
put 'clicks','rw02','hits','name:suresh'
put 'clicks','rw03','hits','name:naresh'

scan 'clicks'
