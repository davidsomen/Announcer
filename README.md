Announce
=========

To be used in conjunction with a cron job to announce the hour, on the hour.

```
# Run at midnight and every hour between 6 and 11pm

0 0,6-23 * * * ~/Announce/announce
```

## Usage

```
announce
```

## Requirements

* Ruby
* mpg123
* AWS credentials (edit in env.yml)

## Install

```
sudo apt install mpg123

bundle install
````
