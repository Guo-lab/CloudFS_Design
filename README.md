This is the README file for CMU 18-746 course project Cloud FS. 

The design document is `siqiguo.pdf`.

> The codebase is not publicly available due to copyright restrictions. Please contact the author for access.



```
student@ip-172-31-9-25:~/mnt/proj2/ckpt3/src$ find ./cloudfs/ -type f \( -name "*.cc" -o -name "*.h" \) | xargs wc -l
   200 ./cloudfs/cloudfs_chunker.cc
   165 ./cloudfs/cloudfs.cc
   125 ./cloudfs/cloudfs_handler.h
   696 ./cloudfs/cloudfs_chunks_manager.cc
   374 ./cloudfs/cloudfs_cache_manager.cc
   746 ./cloudfs/cloudfs_snapshot.cc
  1346 ./cloudfs/cloudfs_handler.cc
   129 ./cloudfs/main.cc
    47 ./cloudfs/cloudfs_utils.h
   388 ./cloudfs/cloudfs.h
   444 ./cloudfs/cloudfs_utils.cc
   566 ./cloudfs/cloudfs_deduper.cc
  5226 total
```