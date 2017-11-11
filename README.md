![SpamScope](https://github.com/SpamScope/spamscope/blob/develop/docs/logo/spamscope.jpg?raw=true "SpamScope")

**spamscope-docker-compose** is an example of Docker Compose with SpamScope and Elasticsearch.

SpamScope is an Advanced Spam Analyzer. For more details visit [GitHub project](https://github.com/SpamScope/spamscope).


## Usage

To use spamscope-docker-compose you should change `.env` file with your configuration and the start all services:


```
$ sudo docker-compose up -d
```

Then you must submit elasticsearch topology:

```
$ sudo docker-compose exec spamscope spamscope-topology submit -g spamscope_elasticsearch 
```

Please check `spamscope-topology submit -h` for more details.


## Apache Storm settings

For more details go to [SpamScope project](https://github.com/SpamScope/spamscope).
