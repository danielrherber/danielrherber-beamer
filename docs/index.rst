.. toctree::
  :maxdepth: 2

install support

Title
=====

Section
-------

Since Pythagoras, we know that :math:`a^2 + b^2 = c^2`.

$$\alpha$$

math:: (a + b)^2 = a^2 + 2ab + b^2

.. math:: e^{i\pi} + 1 = 0
   :label: euler

Euler's identity, equation :eq:`euler`, was elected one of the most
beautiful mathematical formulas.

Subsection
~~~~~~~~~~

You can use ``backticks`` for showing ``highlighted`` code.

`A cool website`_

.. _A cool website: http://sphinx-doc.org

A cool bit of code::

   Some cool Code

.. code-block:: rst

   A bit of **rst** which should be *highlighted* properly.

.. code-block:: matlab

	sin(x).^2 + 1 + abs(x)
	if x > 0
	  disp('a')
	else
	  return
	end