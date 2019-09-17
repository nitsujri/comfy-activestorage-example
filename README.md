# Overview

Blank project as example of ActiveStorage infinite loop when attempting to upload a file via WYISWYG.

```
Rails 6.0.0
Ruby 2.6.4
Comfy 2.0.18
```

## Steps

1. `git clone git@github.com:nitsujri/comfy-activestorage-example.git`
1. `bundle install`
1. `yarn install`
1. `bundle exec rails s`
1. Visit `http://localhost:3000/admin/sites/1/pages/1/edit`
1. Upload image via WYSIWYG.

**Note** Creating DB isn't needed; sqlite db commited to project.
