# sysbench-batchInsert

sysbench：
初始化命令 sysbench --config-file=conf /usr/share/sysbench/oltp_common.lua --tables=1 --table-size=0 prepare
压测命令 sysbench --config-file=conf /usr/share/sysbench/oltp_batch_insert.lua --tables=1 --table-size=0 --mysql-ignore-errors=all run
