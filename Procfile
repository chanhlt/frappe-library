
redis_cache: redis-server config/redis_cache.conf
redis_queue: redis-server config/redis_queue.conf


web: bench serve  --port 8005


socketio: /Users/chanh.le/.nvm/versions/node/v18.19.1/bin/node apps/frappe/socketio.js


watch: bench watch


schedule: bench schedule

worker: OBJC_DISABLE_INITIALIZE_FORK_SAFETY=YES NO_PROXY=* bench worker 1>> logs/worker.log 2>> logs/worker.error.log

