Console App
===
Simple boostrap for any console application.

Just add your Symfony Command class(es) to `src/Command/` directory.
>Note: any command <b>must</b> be a valid Symfony Console Command class 
>(must extend `Symfony\Component\Console\Command\Command` class) 

> Note: root namespace for `src/` directory is set to `App\\`.

And that's it! You can run application by `php bin\console`