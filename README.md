# hello-world
learn how to use.

add a.file
add a.file 1

Hello! this is readme-edits! append new words!
Hello! new line!

Hello! this is new commit: 20170708 11:31
Hello! this is new commit: 20170728 11:39
Hello! this is new commit: 20170728 20:39
Hello! this is new commit: 20170728 21:06
Hello! this is new commit: 20180309 11:48
Hello! this is new commit: 20180309 15:39
Hello! this is new commit: 20180309 15:51
Hello! this is new commit: 20180309 17:43

add b.file
add b.file 1

# 测试gravizo

![Alt text](https://g.gravizo.com/svg?
  digraph G {
    aize ="4,4";
    main [shape=box];
    main -> parse [weight=8];
    parse -> execute;
    main -> init [style=dotted];
    main -> cleanup;
    execute -> { make_string; printf}
    init -> make_string;
    edge [color=red];
    main -> printf [style=bold,label="100 times"];
    make_string [label="make a string"];
    node [shape=box,style=filled,color=".7 .3 1.0"];
    execute -> compare;
  }
)
