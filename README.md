# elastic_wrapper
Wrap any task with an ElasticSearch instance:

```ruby
ESWrapper.wrap do |es|
  # Something that requires elasticsearch
end
```


## Basic Options

```ruby
ESWrapper.wrap port: 9200,
                 verbose: true,
                 managed: true,
                 instance_dir: '/opt/elasticsearch'
```

