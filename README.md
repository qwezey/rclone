# qwezey/rclone

## Usage

    docker run \
        -v CONFIG_FILE:/root/.config/rclone/rclone.conf
        --rm qwezey/rclone SUB_COMMAND

* `CONFIG_FILE` is the path to the rclone configuration file you want to use
* `SUB_COMMAND` the [rclone command](https://rclone.org/commands/rclone/) you want to run

And of course you should bind volumes to the data you want to sync and log files
