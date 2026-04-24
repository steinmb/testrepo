{% include nav.html %}
# My very own website


* [En](dir1/test.md)
* [To](dir2/test.md)
* [En](dir1/test.md)
* [To](dir2/test.md)
* [En](dir1/test.md)
* [To](dir2/test.md)

## Sections

* Each class must be in its own file. 
* Classes must be namespaced. If a module defines a class, the namespace must start with \Drupal\module_name. If it is defined by Drupal Core for use across many modules, the namespace should be \Drupal\Core or \Drupal\Component, with the exception of the global class \Drupal. See https://www.drupal.org/node/1353118 for more about namespaces. 
* In order for the PSR-4-based class auto-loader to find the class, it must be located in a directory corresponding to the namespace. For module-defined classes, if the namespace is \Drupal\module_name\foo\bar, then the class goes under the main module directory in directory src/foo/bar. For Drupal-wide classes, if the namespace is \Drupal\Core\foo\bar, then it goes in directory core/lib/Drupal/Core/foo/bar. See https://www.drupal.org/node/2156625 for more information about PSR-4. 
* Some classes have annotations added to their documentation headers. See the Annotation topic for more information. 
* Standard plugin discovery requires particular namespaces and annotation for most plugin classes. See the Plugin API topic for more information. 
* There are project-wide coding standards for OO code, including naming: https://www.drupal.org/node/608152
* Documentation standards for classes are covered on: https://www.drupal.org/coding-standards/docs#classes
