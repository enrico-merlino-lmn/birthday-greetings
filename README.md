# birthday greetings kata

As you’re a very friendly person, you would like to send a birthday note to all the friends you have. But you have a lot of friends and a bit lazy, it may take some times to write all the notes by hand.

The good news is that computers can do it automatically for you.

Imagine you have a flat file with all your friends :

```csv
last_name, first_name, date_of_birth, email
Doe, John, 1982/10/08, john.doe@foobar.com
Ann, Mary, 1975/09/11, mary.ann@foobar.com
```

And you want to send them a happy birthday email on their birth date :

```csv
Subject: Happy birthday!

Happy birthday, dear <first_name>!
```
How would this software look like ? Try to implement it so you can easily change :

- the way you retrieve the friends data
- the way you send the note


## Additional Features

- Friends born on February, 29th should have their Birthday greeted on February, 28th

- Send a Birthday Reminder note when it is someone else birthday :

```csv
Subject: Birthday Reminder

Dear <first_name>,

Today is <someone_else_first_name> <someone_else_last_name>'s birthday.
Don't forget to send him a message !
```

- Send a single Birthday Reminder note

```csv
Subject: Birthday Reminder

Dear <first_name>,

Today is <full_name_1>, <full_name_2> and <full_name_3>'s birthday.
Don't forget to send them a message !
```


## Origin
This is a copy from: https://gist.github.com/kmos/c746aedc55c1c8271239e37852f7f514

This kata is largely inspired by the work of Matteo Vaccari in http://matteo.vaccari.name/blog/archives/154
