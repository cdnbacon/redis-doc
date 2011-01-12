@complexity

O(N) where N is the number of fields being set.

Sets the specified fields to their respective values in the hash
stored at `key`. This command overwrites any existing fields in the hash.
If `key` does not exist, a new key holding a hash is created.

@return

@status-reply

@examples

    @cli
    HMSET hash field1 "Hello" field2 "World"
    HGET hash field1
    HGET hash field2
