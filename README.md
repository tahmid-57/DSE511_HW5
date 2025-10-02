# DSE511_HW5

The original script was messy. It calculated the average and standard deviation using manual loops, printed some random rows, and made a plot. It worked, but it was not easy to read or change. There were no functions, no error checks, and no tests.

I changed it by creating two small functions: one for computing the average and standard deviation, and one for showing sample rows. I also added a main part that loads the data from a CSV file. Instead of writing loops by hand, I used pandas functions like mean() and std(). This makes the code shorter and easier to understand.

I added some very simple tests at the end of the file. One test checks that the average of [1, 2, 3] is 2.0. I also tested two bad cases: when the data is empty and when the column is missing. Instead of the program crashing, it now prints a message.

This refactoring makes the code easier for me and for others to read. If I want to use the same functions later, I can copy them without copying all the code. It is also easier to debug since the parts are separate.

In short, I realized that breaking a messy script into small functions, using built-in tools, and adding a few tests makes a big difference. Even simple changes can make the code cleaner and safer to use in the future.
