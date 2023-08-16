
`fsneak /mnt/data/dir1`
->
redirect native filesystem to temporary dir
`mount /mnt/data/dir1 /tmp/fsneak_tmp0001` 
`fuse.mount /mnt/data/dir1` 

fuse.unmount /mnt/data/dir1
