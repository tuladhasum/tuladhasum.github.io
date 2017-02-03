---
layout: post
title:  "Useful UNIX Tips"
date:   2017-02-03 15:11:13 +0000
categories: unix macos
---

# Rakefile 
Using rakefile to deploy website
```Ruby
desc 'deploy files to website via rsync'
task :deploy do
  puts 'Getting ready to deploy'
  user = 'username'
  server = 'hostname.example.copm'
  path = '/home/dir/public_html/_sites'
  sh "rsync -rtzh --delete _sites/ #{user}@#{server}:#{path}"
  puts 'Transfer complete'
end
```
