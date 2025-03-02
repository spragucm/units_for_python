# Units for Python
Units for Python standardizes units in Python and provides a mechanism for enforcing typing.

Strongly typed unit classes allow user to indicate and enforce default unit type for any field while still allowing the unit to be easily converted to other units.
  This helps reduce confusion when defining fields like frequency where the default could be Hz, kHz, MHz, or GHz but the code never specified and usage requires additional research

It includes git submodule for [PyUnitWizard](https://github.com/uibcdf/pyunitwizard) by [uibcdf](https://github.com/uibcdf/pyunitwizard/commits?author=dprada)
in order to include a standardized API for working with different forms of physical quantities in Python when using [openmm.unit](https://github.com/openmm/openmm/tree/master/wrappers/python/simtk/unit), [Pint](https://pint.readthedocs.io/en/stable/), or [unyt](https://unyt.readthedocs.io/en/stable/).

