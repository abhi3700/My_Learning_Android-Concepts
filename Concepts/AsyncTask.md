#Introduction
AsyncTask is a generic class, it uses 3 types: AsyncTask<Params, Progress, Result>.

* Params – the input. what you pass to the AsyncTask
* Progress – if you have any updates, passed to onProgressUpdate()
* Result – the output. what returns doInBackground()

Once a task is created, it can be executed like this:
new DownloadTast().execute(url1, url2, urln);

![](https://github.com/abhi3700/My_Learning_Android-Concepts/blob/master/Images/asynctask.jpg)
## Resources - 
* AsyncTask Tutorial With Example Android Studio [Step By Step] - http://abhiandroid.com/programming/asynctask
* Understanding AsyncTask – Once and Forever - https://androidresearch.wordpress.com/2012/03/17/understanding-asynctask-once-and-forever/
