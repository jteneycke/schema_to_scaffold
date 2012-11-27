Schema to Scaffold
==================

After I cross with rake db:schema:dump I felt that it could do a litle more in my case. So here it is.

Usage
-------

The code is very simple and the usage is not friendly but almost.

1. download the zip (or copy paste de code) 
2. extract to folder
3. cd folder
4. if your projects are outside your user folder: edit the main.rb and change the path to point to your schema.rb  (generated with the rake db:schema:dump)
5. ruby main.rb 
6. chose the path to your schema.rb
7. chose your table
8. copy the rails generate scaffold command

* Eight quick steps that will save you a lot of time
* It will give some alerts if your names are not following the rails convention.

read a litle about [rails convention](http://itsignals.cascadia.com.au/?p=7) 

Contributing
------------

Want to contribute? Great!

1. Fork it.
2. Create a branch (`git checkout -b my_schema_to_scafold`)
3. Commit your changes (`git commit -am "Added great stuff"`)
4. Push to the branch (`git push origin my_schema_to_scafold`)
5. Open a [Pull Request][1]
6. That's all!! 

[1]: http://github.com/frenesim/schema_to_scaffold/pulls

Colaborate
------------
if you want to colaborate send me an email please. 