OS作業三
========

編譯方式
--------

- 編譯`main.c` `read_write.c`可以得到完成此次作業要求的版本
- 編譯`single.c` `read_write.c`可以得到_single thread, bubble sort_的版本
- 編譯`rand.c`可以得到亂數產生器

執行方式
--------

`./MT <input_file>`
`./single <input_file>`

亂數產生器執行方式
------------------

`./rand <#_of_random_numbers> > file`

Makefile使用方式
----------------

- `make`得到_正常_版本(`MT`)
- `make verbose`得到_verbose_版本(`MT`)，程式將於執行時印出thread的各種狀態
- `make single`得到_single thread, bubble sort_的版本(`single`)
- `make rand`得到亂數產生器(`rand`)

注意事項
--------

此repositary達到作業要求的核心理念，但*沒有*完全按照作業的spec撰寫。
