
WebInterfaceDocs's documentation
============================================



Another simple header
=====================

.. code-block:: python
	:emphasize-lines: 3,5
	
	def some_function():
		interesting = False
		print 'This line is highlighted'
		print 'This one is not...'
		print '...but this one is '
	print 'Hello world'
	>>>Hello World


.. literalinclude:: subscriber.py
	:language: python

.. code-block:: php	
	:emphasize-lines: 1,3,5

	if (file_exists ("Libraries/database.txt")){
		$data= file("Libraries/database.txt");
		for ($line = 0; $line < count($data); ++$line){
			$userData=explode(" ",$data[$line]);
			if ($userData[3]=="1"){
				$flag=1;
				$userLogged=$userData[0];
				$email=$userData[2];
				$val=strval(intval($userData[4]));
				$simNum=trim(preg_replace('/\s\s+/', ' ', $val));
			}
		}
	}

Guide:
^^^^^
.. toctree::
	:maxdepth: 2
	:caption: Table of Contents

	Getting started
	Help	

     
	



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

testing
