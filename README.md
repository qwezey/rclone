# qwezey/rclone

## Usage

    docker run \
        -v CONFIG_DIR:/root/.config/rclone
        --rm qwezey/rclone SUB_COMMAND

* `CONFIG_DIR` is the path to the directory that contains the desired rclone configuration file `rclone.conf`
* `SUB_COMMAND` the [rclone command](https://rclone.org/commands/rclone/) you want to run

And of course you should bind volumes to the data you want to sync and log files
