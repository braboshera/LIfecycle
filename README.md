1.FirstActivity(lifecycle) sends a message → 2.SecondActivity(MainActivity)
3.SecondActivity(MainActivity) receives message → sends back a reply
4.FirstActivity(lifecycle) receives reply → shows it to the user
5.Uses modern Android Activity Result APIs
6.Avoids deprecated methods
