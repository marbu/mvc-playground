=====================
 java-mvcgui example
=====================

The code here is based on tutorial `Building Graphical User Interfaces with the
MVC Pattern`_.

Build and Execution
===================

To build the code via maven, run ::

   $ mvn package

Then you can execute the jar file generated during the build::

   $ java -jar target/mvcgui-1.0-SNAPSHOT.jar

Notes
=====

In this example and for java in general:

* Model: one or more classess extending `java.util.observable`_
* View: `java.awt`_ gui components implementing `java.util.observer`_ interface
* Controller: listeners in `java.awt.event`_ structure, updates model when user
  interacts with view


.. _`Building Graphical User Interfaces with the MVC Pattern`: http://csis.pace.edu/~bergin/mvc/mvcgui.html
.. _`java.util.observable`: http://docs.oracle.com/javase/8/docs/api/java/util/Observable.html
.. _`java.util.observer`: http://docs.oracle.com/javase/8/docs/api/java/util/Observer.html
.. _`java.awt`: http://docs.oracle.com/javase/8/docs/api/java/awt/package-summary.html
.. _`java.awt.event`: http://docs.oracle.com/javase/8/docs/api/java/awt/event/package-summary.html
