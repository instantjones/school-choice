# school-choice
Data analysis for education's school choice in Indiana project.

Data used in NPR Ed's story ["The Promise And Peril Of School Vouchers"](http://www.npr.org/sections/ed/2017/05/12/520111511/the-promise-and-peril-of-school-vouchers)

Assumptions
-----------

The following things are assumed to be true in this documentation.

* You are running OSX.
* You are using Python 2.7. (Probably the version that came OSX.)
* You have [virtualenv](https://pypi.python.org/pypi/virtualenv) and [virtualenvwrapper](https://pypi.python.org/pypi/virtualenvwrapper) installed and working.

For more details on the technology stack used with the app-template, see our [development environment blog post](http://blog.apps.npr.org/2013/06/06/how-to-setup-a-developers-environment.html).


Bootstrap the project
---------------------

```
cd school-choice
mkvirtualenv school-choice
pip install -r requirements.txt
```

**Problems installing requirements?** You may need to run the pip command as ``ARCHFLAGS=-Wno-error=unused-command-line-argument-hard-error-in-future pip install -r requirements.txt`` to work around an issue with OSX.

Run the notebook
---------------

`
jupyter notebook
`

The homepage of the notebook should open automatically in your preferred browser. Notebooks generally run on `localhost:8888` if it is the sole notebook running.


Data sources
---------------

* Choice Scholarship program annual report: [2014](http://indianapublicmedia.org/stateimpact/files/2014/01/Choice-Scholarship-Program-Annual-Report-012714.pdf), [2016](http://www.doe.in.gov/sites/default/files/news/2015-2016-choice-scholarship-program-report-final-april2016.pdf), [2017](http://www.doe.in.gov/sites/default/files/choice/2016-2017-choice-scholarship-program-report-feb24-final.pdf)

* [Indiana Department of Education Compass](https://compass.doe.in.gov/dashboard/overview.aspx)
