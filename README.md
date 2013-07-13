box-riak
=========
[![Wercker status](https://app.wercker.com/status/0f8896ce9fdf85600a11dd9a2af2a94d)](https://app.wercker.com/project/bykey/0f8896ce9fdf85600a11dd9a2af2a94d)

This service provides an install of riak.  Similar to Wercker's mysql box, riak's files all rest on
a ramdisk.  It uses leveldb for file storage, enabling 2i.  It also enables riak search.  It only uses
one node at the current time.
