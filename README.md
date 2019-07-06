# enter-a-running-docker-container
使用nsenter命令进入docker container后会在container中新建一个-bash，退出也是退出这个新建的-bash，所以退出后并不会使docker container结束。
