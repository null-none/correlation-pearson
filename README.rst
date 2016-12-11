Pearson product-moment correlation coefficient. About algorithm https://en.wikipedia.org/wiki/Pearson_product-moment_correlation_coefficient


=======
Install
=======

.. code-block:: bash

    pip install correlation-pearson

=======
Example
=======

.. code-block:: python

    from correlation_pearson.code import CorrelationPearson

    dmitry = [1, 2, 3, 5, 7, 8]

    joseph = [1, 3, 4, 5, 7, 9]

    correlation = CorrelationPearson()

    print correlation.result(dmitry, joseph)

    0.981460802132
