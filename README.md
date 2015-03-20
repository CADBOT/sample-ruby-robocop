#Continuous Code Review

This is a sample project to show how to have shippable check your rails app's
code style with every commit using rubocop.

This app includes the rubocop gem, a .rubocop.yml file, a custom rake task to
rub rubocop, and of course a shippable.yml file to run this build on shippable!

The shippable.yml checks the rubocop and test results in seperate steps. This
allows you to quickly see if your build failed due to style check fails, or
test fails
