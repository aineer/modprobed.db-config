# modprobed.db-config 
my modprobed.db-config

使用方法:
git clone https://github.com/aineer/modprobed.db-config.git

cp -r modprobed.db $XDG_CONFIG_HOME/modprobed-db.conf
运行modprobed-db store

自动更新数据库：
systemctl --user enable --now modprobed-db
#modprobed-db.service 每隔6小时运行一次modprobed-db store，在开机和关机时也会各运行一次。
