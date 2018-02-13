.. _Users-NeuronModel:

Neuron Models
=============

The simulator covers most widely used neuron models from a simplest Integrate and Fire Model to a rather complex Hodgkin-Huxley(in progress) models. All the models are parametrisable with easy interface to change the parameters. Also, a network can have a combination of these models. For examples, for a layered feedforward network, input layer can be comprised of one model and the next layer be another and so on. 

.. note:: No two models can be in the layer for a layered network

Integrate and Fire 
------------------
Integrate and Fire(*InF*) is one of the simplest and earliest neuron model. The model is given by,  

.. math::

  I(t)=C_\mathrm{m} \frac{d V_\mathrm{m}(t)}{d t}
  
which is simply the time derivative of the law of capacitance, :math:`Q=CV`. With input current applied, the membrane potential increases with time until it reaches a threshold voltage :math:`V_{th}`   


Leaky Integrate and Fire
------------------------


Izhikevich
----------

Custom Models
-------------
