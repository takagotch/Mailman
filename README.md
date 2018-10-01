### Mailman
---

https://github.com/mailman/mailman

```ruby
require 'mailman'
Mailman::Application.run do
  to 'ticket-%id%@ex.org' do
    Ticket.find(param[:id]).add_reply(message)
  end
end
```
```
gem install mailman
gem 'maildir', '< 2.1.0'
```

