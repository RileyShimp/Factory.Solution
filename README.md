# Factory

#### [Riley Shimp](https://www.github.com/rileyshimp)

## Technologies Used

* C#
* .NET
* CSS
* Bootstrap
* MySQL
* Razor View Engine
* EntityCore
* VSCode

## Description

This is an MVC web application built with C# to help a factory manage it's engineers and machines with a database. Users are able to add a list of engineers working at the factory, and for each engineer, add machines that the engineer in licensed to repair. Select a machine, see it's details, and see a list of all engineers licensed to repair that machine.

## Setup/Installation Requirements

### Step 1
Clone the repository:
``` 
$ git clone https://github.com/RileyShimp/Factory.Solution.git 
```
### Step 2
First we'll install .NET, which provides access to the C# language. Follow along with instructions for your operating system provided in the following link: 
https://www.learnhowtoprogram.com/c-and-net/getting-started-with-c/installing-c-and-net

### Step 3
Now .NET and C# should be installed and your computer should recognize the `dotnet` command.
Navigate to the `Factory.Solution` directory in your computer terminal and then to the `Factory` folder.

### Step 4
Create a `appsettings.json` file in the `Factory` directory and add the following code, replacing words in brackets accordingly.

```
{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=riley_shimp;uid=[USERNAME];pwd=[YOUR-PASSWORD-HERE];"
  }
}
```

### Step 5
Open MySQLWorkbench and log into your server (For instructions on downloading MySQLWorkbench visit https://www.learnhowtoprogram.com/c-and-net/getting-started-with-c/installing-and-configuring-mysql)

### Step 6
In your terminal, navigate to the `Factory` folder and run the command `dotnet ef database update`

Lastly, you can run the command `dotnet run`

## Known Bugs

* none

## License

[MIT](https://opensource.org/licenses/MIT)

Copyright (c) 02/25/2022 Riley Shimp