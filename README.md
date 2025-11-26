1.FirstActivity(lifecycle) sends a message → SecondActivity(MainActivity)
2.SecondActivity(MainActivity) receives message → sends back a reply
3.FirstActivity(lifecycle) receives reply → shows it to the user
4.Uses modern Android Activity Result APIs
5.Avoids deprecated methods
